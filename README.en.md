# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey is a native macOS shortcut launcher that completes app activation and window selection in one key flow.

- Built with native Swift for fast response, low overhead, and minimal interruption
- Supports Left/Right Command (0 delay or custom delay), Left/Right Option (0 delay or custom delay), and Space trigger (minimum 0.2s delay to avoid affecting normal typing)
- Optimized for high-frequency workflows and smoother window switching
- Local-first by design, without default reliance on cloud behavior analytics

## Website

- Zeabur homepage: https://telunkey.zeabur.app

> [!IMPORTANT]
> If you cannot access Zeabur at all, TelunKey may not fit your current environment. If you can solve network issues on your side, TelunKey is worth trying and can improve your efficiency.

## UI Preview

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="Trigger hint" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome scenario" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="Settings" src="./images/shezhi.png?v=20260329" width="100%" />

## System Requirements

- macOS 14.0 or later

## Download

- Latest release (DMG): https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- All releases: https://github.com/telungit/TelunKey/releases

## Installation

1. Download and open `TelunKey.dmg`
2. Drag `TelunKey.app` into Applications
3. Do not launch the app yet. First, double-click `2. Run Once After Install.command` inside the DMG
4. Open TelunKey after the repair finishes
5. Only if the script fails, run the following command manually in Terminal

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## Permissions

TelunKey requires the following permissions for full functionality:

- Accessibility: listen to global keyboard events
- Screen Recording: generate window thumbnails

## Privacy

TelunKey follows a local-first strategy. Core data stays on your machine.

## Feedback

- Telegram: https://t.me/telungram
