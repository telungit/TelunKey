<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 图标" />

# TelunKey

**键盘直达窗口，手势摆放窗口**

按住一个键，敲一两个字母，直达任意应用的任意窗口；触控板一滑，窗口就位。

[![最新版本](https://img.shields.io/github/v/release/telungit/TelunKey?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[官网](https://www.telunkey.shop) · [安装](#快速上手) · [反馈](#反馈)

简体中文 | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## 两三个键，直达应用

按住触发键（左 / 右 Command、左 / 右 Option 或空格），输入一到三个字母：应用没开就打开，只有一个窗口就直接聚焦，有多个窗口就弹出选择器。按住期间会列出全部绑定，不必死记。

<img src="./images/zh/hint.png" width="100%" alt="按住触发键后列出全部绑定的提示菜单" />

## 一眼选中窗口

选择器用缩略图列出应用的所有窗口，按数字或字母键一键选中，空格回到最近使用的那个。窗口分散在多个桌面时，卡片会标出所在桌面。

<img src="./images/zh/picker.png" width="100%" alt="带缩略图的窗口选择器" />

## 触控板一滑，窗口就位

- **触发手势**：按住触发键在触控板上滑动，把指针下的窗口摆到半屏、四分之一屏或最大化。
- **全局手势**：三指滑动、轻点或按下，可绑定窗口操作、快捷键或单个按键。
- **跨显示器**：全局手势一路滑出边缘，窗口按比例移到另一块显示器。
- 每个手势都能重新映射，并附带只预览、不执行的练习模式。

<p align="center"><img src="./images/zh/gestures.png" width="380" alt="触发手势设置页" /></p>

## 原生、轻量

纯 Swift 编写，没有第三方依赖，常驻菜单栏。配置保存在本机，可导入导出；界面支持 12 种语言。

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

## 快速上手

需要 macOS 14 及以上，并已安装 [Homebrew](https://brew.sh/)：

```bash
brew install --cask telungit/tap/telunkey
```

首次打开会有向导，带你完成授权、触发键、快捷键和手势设置。之后可在应用内更新，或执行：

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## 权限与隐私

| 权限 | 用途 |
| --- | --- |
| 辅助功能（必需） | 监听触发键与手势，切换、调整窗口 |
| 屏幕录制（可选） | 生成窗口缩略图；未授予时显示应用图标，切换不受影响 |

配置保存在本机，授权凭证存放在钥匙串。TelunKey 只在验证授权和检查更新时联网，不收集使用数据。

## 免费与授权

免费版可绑定 5 个应用，其余功能完整可用；在[官网](https://www.telunkey.shop)购买永久授权后不限数量。

## 反馈

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
