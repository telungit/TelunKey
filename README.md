# TelunKey

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md)

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

https://github.com/user-attachments/assets/762f43e0-eac3-4ffa-ba33-f68f720d2627

![触发提示](./images/datishi.png)
![Chrome 场景](./images/chrome.png)
![设置界面](./images/shezhi.png)

## 系统要求

- macOS 14.0 及以上

## 下载

- 最新版本（DMG）：https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- 所有版本：https://github.com/telungit/TelunKey/releases

## 安装

1. 下载并打开 `TelunKey.dmg`
2. 将 `TelunKey.app` 拖到“应用程序”
3. 先不要打开 App，先双击 DMG 内的 `一键修复.command`
4. 看到修复完成后，再打开 TelunKey
5. 只有脚本执行失败时，才需要在终端中手动执行如下命令。

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## 权限说明

TelunKey 需要以下权限以启用完整功能：

- 辅助功能：监听全局键盘事件
- 屏幕录制：生成窗口缩略图

## 隐私

TelunKey 采用本地优先策略，核心数据保留在本机。

## 反馈

- Telegram: https://t.me/telungram
