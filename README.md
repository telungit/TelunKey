# TelunKey

TelunKey 是一款原生 macOS 快捷键启动器，用一轮按键完成应用激活与窗口选择。

- 原生 Swift 实现，响应快、开销小、干扰低
- 支持左/右 Command（0延迟或自定义延迟）、左/右 Option（0延迟或自定义延迟）、Space 触发（最低0.2秒延迟）
- 面向高频工作流优化窗口切换体验
- 本地优先，默认不依赖云端行为分析

## 官网

- Vercel 主页：https://telunkey.vercel.app/zh

## 界面预览

![触发提示](./images/datishi.png)
![Chrome 场景](./images/chrome.png)
![设置界面](./images/shezhi.png)

## 系统要求

- macOS 14.0 及以上

## 下载

- 最新版本（DMG）：https://github.com/hanyiwen/TelunKey/releases/latest/download/TelunKey.dmg
- 所有版本：https://github.com/hanyiwen/TelunKey/releases

## 安装

1. 下载并打开 `TelunKey.dmg`
2. 将 `TelunKey.app` 拖到“应用程序”
3. 首次启动若被系统拦截，执行：

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

4. 重新打开 TelunKey

## 权限说明

TelunKey 需要以下权限以启用完整功能：

- 辅助功能：监听全局键盘事件
- 屏幕录制：生成窗口缩略图

## 隐私

TelunKey 采用本地优先策略，核心数据保留在本机。

## 反馈

- Telegram: https://t.me/telungram
