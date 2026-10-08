# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey 是一款原生 macOS 快捷键启动器，用一轮按键完成应用激活与窗口选择。

- 原生 Swift 实现，响应快、开销小、干扰低
- 支持左/右 Command（0延迟或自定义延迟）、左/右 Option（0延迟或自定义延迟）、Space 触发（最低0.2秒延迟，从而做到不影响日常输入）
- 面向高频工作流优化窗口切换体验
- 本地优先，默认不依赖云端行为分析

## 官网

- Zeabur 主页：https://telunkey.zeabur.app

> [!IMPORTANT]
> 如果始终无法正常访问 Zeabur，其实您应该不会有使用 TelunKey 的场景；如果您有能力且有耐心解决网络问题，您一定要试试 TelunKey，我相信他绝对能提高您的效率。

## 界面预览

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="触发提示" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome 场景" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="设置界面" src="./images/shezhi.png?v=20260329" width="100%" />

## 系统要求

- macOS 14.0 及以上

## 安装

已安装 [Homebrew](https://brew.sh/) 的用户可以执行：

```bash
brew update
brew install --cask telungit/tap/telunkey
```

安装后，从“应用程序”打开 TelunKey。

## 更新

退出 TelunKey 后执行：

```bash
brew update
brew upgrade --cask --greedy telungit/tap/telunkey
```

也可以在应用内检查更新。

## 权限说明

TelunKey 需要以下权限以启用完整功能：

- 辅助功能：监听全局键盘事件
- 屏幕录制：生成窗口缩略图

## 隐私

TelunKey 采用本地优先策略，核心数据保留在本机。

## 反馈

- Telegram: https://t.me/telungram
