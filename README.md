# CodeVibe Marketplace

Official marketplace for the CodeVibe Claude plugin - control Claude Code from your phone.

## Quick Install

```bash
curl -fsSL https://quantiya.ai/codevibe/install.sh | bash
```

This installs everything automatically: Node.js, tmux, Claude Code, CodeVibe, and the Claude plugin.

### Manual Install

```bash
npm install -g @quantiya/codevibe
claude plugin marketplace add https://github.com/hendryyeh/quantiya-codevibe-marketplace
claude plugin install codevibe-claude@codevibe-marketplace
codevibe-claude login
```

## What is CodeVibe?

CodeVibe lets you control AI coding agents (Claude Code, Gemini CLI, Codex CLI) from your phone:

- **Real-time Sync** - See desktop conversations on mobile instantly
- **Mobile Control** - Send prompts from your phone
- **Interactive Prompts** - Answer permission dialogs remotely
- **File Diff Review** - See full diffs with syntax highlighting
- **Push Notifications** - Get alerted when your agent needs input
- **Voice Input** - Dictate prompts using speech-to-text
- **Image Attachments** - Send screenshots and photos
- **E2E Encrypted** - AES-256-GCM encryption for all content
- **Multi-Agent** - Supports Claude Code, Gemini CLI, and Codex CLI

## Requirements

- macOS, Windows, or Linux
- Node.js 18+
- tmux

## Links

- **Landing Page:** [quantiya.ai/codevibe](https://quantiya.ai/codevibe)
- **Claude Plugin:** [quantiya-codevibe-claude-plugin](https://github.com/hendryyeh/quantiya-codevibe-claude-plugin)
- **Gemini Plugin:** [quantiya-codevibe-gemini-plugin](https://github.com/hendryyeh/quantiya-codevibe-gemini-plugin)
- **Codex Plugin:** [quantiya-codevibe-codex-plugin](https://github.com/hendryyeh/quantiya-codevibe-codex-plugin)
- **Android:** [Google Play](https://play.google.com/store/apps/details?id=ai.quantiya.app.codevibe)
- **iOS:** [App Store](https://apps.apple.com/app/id6756500217)

## License

MIT License - see [LICENSE](LICENSE)
