# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey is a native macOS shortcut launcher that completes app activation and window selection in a single key flow.

- Built with native Swift for rapid response, low resource footprint, and minimal distraction
- Supports Left/Right Command (zero or custom delay), Left/Right Option (zero or custom delay), and Space trigger (minimum 0.2s delay to avoid disrupting daily typing)
- Optimized for high-frequency workflows with seamless window switching
- Local-first by design, with no reliance on cloud behavioral analytics by default

## Website

- Zeabur homepage: https://telunkey.zeabur.app

> [!IMPORTANT]
> If you cannot access Zeabur reliably, you likely will not have a use case for TelunKey. However, if you have both the capability and the patience to navigate network hurdles, you definitely should give TelunKey a try—I firmly believe it will boost your productivity.

## UI Preview

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Trigger hint" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome scenario" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Settings" src="./images/shezhi.png?v=20260329" width="100%" />

## System Requirements

- macOS 14.0 or later

## Installation

Users with [Homebrew](https://brew.sh/) installed can run:

```bash
brew install --cask telungit/tap/telunkey
```

After installation, open TelunKey from Applications.

## Update

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

You can also check for updates directly within the app.

## Permissions

TelunKey requires the following permissions for full functionality:

- Accessibility: listen to global keyboard events
- Screen Recording: generate window thumbnails

## Privacy

TelunKey follows a local-first strategy. Core data stays on your machine.

## Feedback

- Telegram: https://t.me/telungram
