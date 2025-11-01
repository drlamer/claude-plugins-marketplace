# roblox-game-design-partner

Transform game concepts into polished Roblox experiences

## Installation

### From Marketplace (Recommended)

```bash
# Add the marketplace (one-time setup)
/plugin marketplace add drlamer/claude-plugins-marketplace

# Install the plugin
/plugin install roblox-game-design-partner@drlamer
```

### Local Installation

```bash
# Clone the repository
git clone https://github.com/drlamer/roblox-game-design-partner-plugin.git

# Install the plugin
claude plugin install ./roblox-game-design-partner-plugin
```

### Verify Installation

```bash
/plugin list
# Should show: roblox-game-design-partner v1.0.0
```

## Commands

- `/roblox-design` - Build complete Roblox games through 10-phase development workflow

## Agents

- **roblox-orchestrator-agent**: Main coordinator for full game builds - plans and delegates all 10 development phases
- **roblox-architect-agent**: Foundation and architecture specialist (Phases 1-2)

## Skills

- **luau-code-generation**: Generate Roblox Luau scripts with proper API usage and error handling
- **quality-gate-validation**: Validate game quality across 3 tiers (Essential, Enhancement, Sophistication)

## Usage

After installation, use the `/roblox-design` command with your game concept:

```bash
/roblox-design "Create a medieval castle with interactive towers and a drawbridge"
```

The plugin will guide you through a 10-phase development workflow to build your complete Roblox game.
