# LilAgentsClode

![LilAgentsClode](hero-thumbnail.png)

**LilAgentsClode** is a fun little fork of lil agents—same idea, new faces. Tiny AI companions that live on your macOS dock, now starring custom **lil dock clodes**: a bouncy happy clode and a mellower sad clode, each with walk and idle loops rendered from transparent HEVC video.

Click either clode to open a Claude AI terminal in a themed popover. They walk, they think, they vibe.

## Features

- Animated characters rendered from transparent HEVC video
- Click a character to chat with Claude AI in a themed popover terminal
- Four visual themes: Peach, Midnight, Cloud, Moss
- Thinking bubbles with playful phrases while Claude works
- Sound effects on completion
- First-run onboarding with a friendly welcome
- Auto-updates via Sparkle

## Requirements

- macOS Sonoma (14.0+)
- [Claude Code CLI](https://claude.ai/download)

## Building

Open `lil-agents.xcodeproj` in Xcode and hit run.

## Privacy

LilAgentsClode runs entirely on your Mac; the app does not add new telemetry beyond what the upstream **lil agents** project already describes.

- **Your data stays local.** The app plays bundled animations and calculates your dock size to position the characters. No project data, file paths, or personal information is collected or transmitted by the app itself.
- **Claude AI.** Conversations are handled by the Claude Code CLI process running locally. The app does not intercept, store, or transmit your chat content. Any data sent to Anthropic is governed by their terms and privacy policy.
- **No accounts.** No login, no user database, no analytics in the app.
- **Updates.** Sparkle checks for updates and sends your app version and macOS version. Nothing else.

## License

MIT License. See [LICENSE](LICENSE) for details.
