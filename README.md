# drlamer's Claude Code Plugin Marketplace

Official marketplace for drlamer's Claude Code plugins.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add drlamer/claude-plugins-marketplace
```

## Available Plugins

### roblox-game-design-partner v1.0.0

Transform game concepts into polished Roblox experiences through a 10-phase development workflow.

**Install**:
```bash
/plugin install roblox-game-design-partner@drlamer
```

**Category**: Development
**Repository**: [drlamer/roblox-game-design-partner-plugin](https://github.com/drlamer/roblox-game-design-partner-plugin)

---

## For Plugin Developers

This marketplace follows the official Anthropic marketplace structure. Each plugin is maintained in its own repository and referenced in the marketplace.json file.

### Structure

```
claude-plugins-marketplace/
├── .claude-plugin/
│   └── marketplace.json    # Plugin catalog
└── README.md               # This file
```

### Adding Plugins to This Marketplace

Plugins are referenced by their GitHub repositories:

```json
{
  "name": "plugin-name",
  "description": "Plugin description",
  "source": "github.com/drlamer/plugin-name-plugin",
  "category": "development|productivity|security",
  "version": "1.0.0"
}
```

## Support

For issues or questions:
- Plugin-specific: Open issue in the plugin's repository
- Marketplace: Open issue in this repository
