<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey icon" />

# TelunKey

**Window switching for macOS · Keys and trackpad**

Hold a trigger key and type one to three keys to reach any app or window. Swipe the trackpad to put it in place.

[![Latest release](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[Install](#install) · [Feedback](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | English | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Direct keys

Hold a trigger key (left / right Command, left / right Option, or Space) and enter the one to three keys assigned to an app. If the app is not running, it opens; if it has one window, that window gets focus; if it has several, the selector appears. Hold the trigger key to view all bindings.

<img src="./images/en/hint.png" width="100%" alt="Hint menu listing all bindings while the trigger key is held" />

## Keyboard selector

The selector arranges window thumbnails in keyboard order: 1–0, Q–P, A–L, Z–M, with up to 36 windows per page. Press the corresponding number or letter to select a window.

- Space: back to the window you used last
- Windows on other desktops show which desktop they are on
- [ and ] change pages, Esc cancels, or just click

<img src="./images/en/picker.png" width="100%" alt="Window selector" />

## Trigger gestures

Hold the trigger key and swipe two fingers on the trackpad to arrange the window under the pointer to fill half or a quarter of the screen, or to maximize it.

- Up, down, left, right: halves. Four diagonals: quarters
- Up then down without lifting: maximize, keeping the menu bar and Dock
- Slide into the cancel zone to cancel, slide back to choose again

### Three-finger gestures

Once enabled, eight directions, back-and-forth swipes, tap, double tap, long touch and press can each send a shortcut, a single key, a middle click, or a window action.

- Off by default. If it conflicts with a system three-finger gesture, Settings lists it and links to the fix
- Across displays: continue a three-finger gesture outward past the cancel zone to move the window to another display, keeping its proportions.
- Every gesture can be remapped, and a practice mode previews actions without running them.

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Trigger gesture settings" /></p>

## Runtime and settings

Written in pure Swift with no third-party dependencies, living in the menu bar. Settings stay on your Mac and can be imported or exported; the interface is available in 12 languages.

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## Get started

Requires macOS 14 or later and [Homebrew](https://brew.sh/):

```bash
brew install --cask telungit/tap/telunkey
```

On first launch, a setup guide walks you through permissions, trigger keys, shortcuts, and gestures. Update from within the app, or run:

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## Permissions

| Permission | Used for |
| --- | --- |
| Accessibility (required) | Detecting trigger keys and gestures; switching and arranging windows |
| Screen Recording (optional) | Window thumbnails; without it, app icons are shown and switching still works |

<a id="feedback"></a>

## Feedback

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
