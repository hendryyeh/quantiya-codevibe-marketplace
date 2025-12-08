# Claude Companion Marketplace

Official marketplace for the Claude Companion plugin - control Claude Code from your iPhone.

## Installation

### Step 1: Add this Marketplace

Inside Claude Code, run:

```
/plugin marketplace add hendryyeh/claude-companion-marketplace
```

### Step 2: Install the Plugin

```
/plugin install claude-companion
```

### Step 3: Complete Setup

After installation, follow the prompts to:

1. Reload your shell: `source ~/.zshrc`
2. Login: `claude-companion login`
3. Start Claude Code: `claude-companion`
4. Download the iOS app from the App Store

## What is Claude Companion?

Claude Companion lets you control Claude Code from your iPhone:

- **Real-time Sync** - See desktop conversations on mobile instantly
- **Mobile Control** - Send prompts from your iPhone
- **Locked Screen Support** - Works even when your Mac is locked
- **Interactive Prompts** - Answer permission dialogs remotely
- **Voice Input** - Dictate prompts using iOS speech-to-text
- **Image Attachments** - Send screenshots and photos

## Requirements

- macOS
- Node.js 18+
- tmux (`brew install tmux`)
- Claude Code with plugin system

## Links

- **Plugin Repository:** [quantiya-claude-companion-plugin](https://github.com/hendryyeh/quantiya-claude-companion-plugin)
- **iOS App:** Available on the App Store (search "Claude Companion")

## License

MIT License - see [LICENSE](LICENSE)
