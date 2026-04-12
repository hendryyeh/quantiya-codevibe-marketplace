# CodeVibe Marketplace

Official Claude Code plugin marketplace for CodeVibe — control Claude Code, Gemini CLI, and Codex CLI from your phone.

## Quick Install

```bash
curl -fsSL https://quantiya.ai/codevibe/install.sh | bash
```

This installs everything automatically: Node.js, tmux, Claude Code, the `@quantiya/codevibe` meta-package, and the Claude plugin.

### Manual Install

```bash
npm install -g @quantiya/codevibe
claude plugin marketplace add https://github.com/hendryyeh/quantiya-codevibe-marketplace
claude plugin install codevibe-claude@codevibe-marketplace
codevibe login
```

## What is CodeVibe?

CodeVibe lets you control AI coding agents (Claude Code, Gemini CLI, Codex CLI) from your phone:

- **Real-time Sync** — See desktop conversations on mobile instantly (~100–500ms latency)
- **Mobile Control** — Send prompts from your phone; executes immediately in your terminal
- **Interactive Prompts** — Answer permission dialogs remotely with full file diff preview
- **Voice Input** — Dictate prompts using speech-to-text
- **Image Attachments** — Send screenshots and photos with your messages
- **Push Notifications** — Get alerted when your agent needs input
- **E2E Encrypted** — AES-256-GCM encryption for all content
- **Multi-Agent** — One mobile app controls Claude Code, Gemini CLI, and Codex CLI sessions side-by-side

## Requirements

- **macOS, Linux, or WSL Ubuntu** — Windows without WSL is not supported
- **Node.js** 18+
- **tmux** — `brew install tmux` on macOS, `apt install tmux` on Linux/WSL
- **Claude Code** with plugin system enabled (for the Claude plugin)

## Published packages

All CodeVibe packages are published to npm under the [`@quantiya`](https://www.npmjs.com/org/quantiya) org:

- **[@quantiya/codevibe](https://www.npmjs.com/package/@quantiya/codevibe)** — meta-package with `codevibe login`, `codevibe update`, and all agent wrappers
- **[@quantiya/codevibe-core](https://www.npmjs.com/package/@quantiya/codevibe-core)** — shared library: keychain, E2E crypto, AppSync client, session lifecycle
- **[@quantiya/codevibe-claude-plugin](https://www.npmjs.com/package/@quantiya/codevibe-claude-plugin)** — Claude Code plugin
- **[@quantiya/codevibe-gemini-plugin](https://www.npmjs.com/package/@quantiya/codevibe-gemini-plugin)** — Gemini CLI plugin
- **[@quantiya/codevibe-codex-plugin](https://www.npmjs.com/package/@quantiya/codevibe-codex-plugin)** — Codex CLI plugin

## Mobile apps

- **iOS:** [App Store](https://apps.apple.com/app/id6756500217)
- **Android:** [Google Play](https://play.google.com/store/apps/details?id=ai.quantiya.app.codevibe)

## Links

- **Landing Page:** [quantiya.ai/codevibe](https://quantiya.ai/codevibe)
- **Support:** [quantiya.ai/support](https://quantiya.ai/support)
- **Privacy Policy:** [quantiya.ai/privacy](https://quantiya.ai/privacy)

## License

MIT License — see [LICENSE](LICENSE)
