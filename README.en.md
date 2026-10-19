<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey icon" />

# TelunKey

**Reach any window from the keyboard. Arrange it with a swipe.**

Hold one key and type a letter or two to jump to any window of any app. Swipe on the trackpad, and the window falls into place.

[![Latest release](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[Website](https://www.telunkey.shop) · [Install](#install) · [Feedback](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | English | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## Two or three keys to any app

Hold a trigger key (left / right Command, left / right Option, or Space) and type one to three letters. If the app isn't running, it opens; with one window, that window comes forward; with several, a picker appears. While you hold the key, every binding is listed, so there's nothing to memorize.

<img src="./images/en/hint.png" width="100%" alt="Hint menu listing all bindings while the trigger key is held" />

## Pick the right window at a glance

The picker shows every window of the app as a thumbnail. Press a number or letter to choose one, or Space for the most recently used. When windows are spread across desktops, each card shows which desktop it's on.

<img src="./images/en/picker.png" width="100%" alt="Window picker with thumbnails" />

## Swipe, and the window falls into place

- **Trigger gestures**: hold the trigger key and swipe on the trackpad to snap the window under the pointer to a half, a quarter, or full screen.
- **Global gestures**: bind three-finger swipes, taps, or clicks to window actions, keyboard shortcuts, or single keys.
- **Across displays**: carry a global gesture past the edge to move the window to another display, keeping its proportions.
- Every gesture can be remapped, and a practice mode previews actions without running them.

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Trigger gesture settings" /></p>

## Native and lightweight

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

## Permissions and privacy

| Permission | Used for |
| --- | --- |
| Accessibility (required) | Detecting trigger keys and gestures; switching and arranging windows |
| Screen Recording (optional) | Window thumbnails; without it, app icons are shown and switching still works |

Settings are stored on your Mac, and the license credential is kept in the Keychain. TelunKey goes online only to verify your license and check for updates, and collects no usage data.

## Free and licensed

The free version lets you bind up to 5 apps, with every other feature included. A lifetime license from the [website](https://www.telunkey.shop) removes the limit.

<a id="feedback"></a>

## Feedback

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
