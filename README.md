<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 图标" />

# TelunKey

**macOS 窗口切换 · 键盘与触控板**

按住触发键，一到三个键直达应用与窗口；触控板一滑，把窗口摆好。

[![最新版本](https://img.shields.io/github/v/release/telungit/TelunKey?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[官网](https://www.telunkey.shop) · [安装](#快速上手) · [反馈](#反馈)

简体中文 | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## 按键直达

按住触发键（左 / 右 Command、左 / 右 Option 或空格），输入绑定的一到三个键。应用未运行时会打开；只有一个窗口时直接聚焦；有多个窗口时显示选择器。按住触发键期间可查看全部绑定。

<img src="./images/zh/hint.png" width="100%" alt="按住触发键后列出全部绑定的提示菜单" />

## 键位选择器

选择器按键盘布局排列窗口缩略图：1–0、Q–P、A–L、Z–M，每页最多 36 个窗口。按对应的数字或字母键选择。

- 空格：回到最近用过的那个窗口
- 其他桌面的窗口会标出所在桌面
- [ 和 ] 翻页，Esc 取消，也可以直接点

<img src="./images/zh/picker.png" width="100%" alt="窗口选择器" />

## 触发手势

按住触发键，在触控板上双指滑动，可将指针下的窗口放到半屏、四分之一屏或最大化。

- 上下左右：半屏；四个斜向：四分之一屏
- 不抬手先上再下：最大化，保留菜单栏和 Dock
- 滑进取消区就取消，滑回来还能重选

### 三指全局手势

开启后，三指的八个方向、往返、轻点、双击、长触与按下，每一种都能绑定组合快捷键、单键、鼠标中键或窗口操作。

- 默认关闭；与系统三指手势冲突时，设置页会逐项列出并给出入口
- 跨显示器：三指全局手势滑过取消区后继续向外滑，可将窗口移到另一块显示器，并保留窗口比例。
- 每个手势都能重新映射，并附带只预览、不执行的练习模式。

<p align="center"><img src="./images/zh/gestures.png" width="380" alt="触发手势设置页" /></p>

## 运行与配置

纯 Swift 编写，没有第三方依赖，常驻菜单栏。配置保存在本机，可导入导出；界面支持 12 种语言。

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

## 快速上手

需要 macOS 14 及以上，并已安装 [Homebrew](https://brew.sh/)：

```bash
brew install --cask telungit/tap/telunkey
```

首次打开会有向导，带你完成权限、触发键、快捷键和手势设置。之后可在应用内更新，或执行：

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## 权限与隐私

| 权限 | 用途 |
| --- | --- |
| 辅助功能（必需） | 监听触发键与手势，切换、调整窗口 |
| 屏幕录制（可选） | 生成窗口缩略图；未授予时显示应用图标，切换不受影响 |

TelunKey 以本地运行为主，不采集你的键击内容与窗口行为数据。

Dodo Payments 处理付款、购买邮箱、授权码和设备激活记录；激活时会向其发送授权码和设备名称以管理两台设备的名额。授权码与本机激活记录保存在系统钥匙串中。TelunKey 不保存银行卡信息，使用时无需注册网站账号。

## 免费版与永久更新计划

免费版最多绑定 5 个应用，全部功能可用，不限使用时间，无需注册。永久更新计划一次付费 ¥18，不限绑定数量，包含后续更新。

完成支付后查收 Dodo Payments 发来的授权码邮件，在 TelunKey 设置的“授权”页输入即可，无需注册账号。可在 2 台 Mac 上使用；换机前先在旧设备上解绑。

[方案与条款](https://www.telunkey.shop/zh/terms)

## 反馈

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
