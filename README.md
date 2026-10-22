<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 图标" />

# TelunKey

**macOS 窗口切换 · 键盘与触控板**

按住触发键，一到三个键直达应用与窗口；触控板一滑，把窗口摆好。

[![最新版本](https://img.shields.io/github/v/release/telungit/TelunKey?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[安装](#快速上手) · [反馈](#反馈)

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

按住触发键，用已启用的单指、双指或三指滑动，将鼠标下的窗口放到半屏、四分之一屏或最大化。

- 上下左右：半屏；四个斜向：四分之一屏
- 不抬手先上再下：最大化，保留菜单栏和 Dock
- 滑进取消区就取消，滑回来还能重选

<p align="center"><img src="./images/zh/gestures.png" width="380" alt="触发手势设置页" /></p>

## 三指与四指全局手势

无需按住触发键。三指滑动、往返，以及三指或四指的轻点、双击与按下点击，都能绑定快捷键、单键、鼠标中键或窗口操作；长触固定用于移屏。所有动作作用于本轮锁定的鼠标下窗口，并提供只预览、不执行的练习模式。

若与系统三指滑动、拖移或轻点查询冲突，TelunKey 会列出实际开启的项并直接跳转到对应的系统设置页，返回后自动复查，不会自动修改系统设置。冲突解除前，三指滑动与三指长触暂不接管，点按仍可单独使用。

## 长触移屏

显示器在左边、右边，还是上方？长触展开与系统布局一致的小地图，滑到想去的屏幕，抬手就把窗口按可用区域比例移过去。

- 四指长触即可选屏（普通四指滑动仍归 macOS）；也支持就绪后的三指，或按住触发键配已启用的一至三指
- 窗口移入目标显示器当前显示的桌面；全屏窗口或正在显示全屏应用的目标屏不参与
- 确认前可随时滑回；在原屏或空白处抬手、提前松开触发键，或按 Esc 均可取消

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

## 权限

| 权限 | 用途 |
| --- | --- |
| 辅助功能（必需） | 监听触发键与手势，切换、调整窗口 |
| 屏幕录制（可选） | 生成窗口缩略图；未授予时显示应用图标，切换不受影响 |

## 反馈

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
