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

Hold the trigger key and swipe with your enabled one-, two-, or three-finger gesture to arrange the window under the pointer in halves, quarters, or maximized.

- Up, down, left, right: halves. Four diagonals: quarters
- Up then down without lifting: maximize, keeping the menu bar and Dock
- Slide into the cancel zone to cancel, slide back to choose again

<p align="center"><img src="./images/en/gestures.png" width="380" alt="Trigger gesture settings" /></p>

## Three- and four-finger global gestures

No trigger key needed. Map three-finger swipes and return strokes, plus three- or four-finger taps, double taps, and physical clicks to shortcuts, single keys, middle clicks, or window operations. Touch and hold is reserved for moving between displays. Actions use the window locked under the pointer.

On for new installs; upgrades preserve existing settings. Touch and hold is reserved for moving between displays. Other gestures can be remapped; practice previews actions without running them.

Before using three-finger swipes or touch-and-hold display selection, turn off system three-finger dragging and switch system horizontal and vertical swipes to four fingers or turn them off. TelunKey lists only enabled conflicts and links to Trackpad → More Gestures or Accessibility → Pointer Control → Trackpad Options. It checks again when you return, and you can set this up later. Until conflicts are resolved, three-finger swipes and display selection stay inactive; taps and clicks remain available. System Look Up conflicts are shown separately. TelunKey never changes System Settings automatically.

## Hold to move between displays

Left, right, or above? Touch and hold to reveal a map that follows your macOS display arrangement. Slide to the display you want, then lift to move the window.

- Hold four fingers still, then slide to choose a display; three fingers after setup, or a held trigger key with your enabled one to three fingers, also work
- Choose by display arrangement; the window keeps its proportional placement within usable screen areas
- You can slide back before confirming; lift on the source display or empty space to cancel. You can also press Esc to cancel.

Regular four-finger swipes stay with macOS. Hold four fingers still first; only after display selection starts does TelunKey temporarily take over that gesture. Lift to return control to macOS.

You can move it to the desktop currently visible on another display. A single display has no destination. Full-screen windows are excluded, and a display showing a full-screen app is unavailable. Lift on the source, empty space, or an unavailable display to cancel. With trigger gestures, keep the trigger key held; releasing it early also cancels.

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
