# CodeVibe Marketplace

Official marketplace for the CodeVibe Claude plugin - control Claude Code from your iPhone.

## Installation

### Step 1: Install Wrapper Command

Install the CodeVibe wrapper command via npm (puts `codevibe-claude` in your PATH):

```bash
npm install -g @quantiya/codevibe
```

### Step 2: Add this Marketplace

Inside Claude Code, run:

```
/plugin marketplace add https://github.com/hendryyeh/quantiya-codevibe-marketplace
```

### Step 3: Install the MCP Plugin

```
/plugin install codevibe-claude
```

### Step 4: Login and Start

```bash
codevibe-claude login    # Opens browser for authentication
codevibe-claude          # Start Claude Code with mobile support
```

Download the iOS app from the App Store (search "CodeVibe").

## What is CodeVibe?

CodeVibe lets you control AI coding agents (Claude Code, Gemini CLI, Codex CLI) from your iPhone:

- **Real-time Sync** - See desktop conversations on mobile instantly
- **Mobile Control** - Send prompts from your iPhone
- **Locked Screen Support** - Works even when your Mac is locked
- **Interactive Prompts** - Answer permission dialogs remotely
- **Voice Input** - Dictate prompts using iOS speech-to-text
- **Image Attachments** - Send screenshots and photos
- **Multi-Agent** - Supports Claude Code, Gemini CLI, and Codex CLI

## Requirements

- macOS
- Node.js 18+
- tmux (`brew install tmux`)
- Claude Code with plugin system

## Links

- **Claude Plugin Repository:** [quantiya-codevibe-claude-plugin](https://github.com/hendryyeh/quantiya-codevibe-claude-plugin)
- **Gemini Plugin Repository:** [quantiya-codevibe-gemini-plugin](https://github.com/hendryyeh/quantiya-codevibe-gemini-plugin)
- **Codex Plugin Repository:** [quantiya-codevibe-codex-plugin](https://github.com/hendryyeh/quantiya-codevibe-codex-plugin)
- **iOS App:** Available on the App Store (search "CodeVibe")

## License

MIT License - see [LICENSE](LICENSE)
