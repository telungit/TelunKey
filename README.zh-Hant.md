# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey 是一款原生 macOS 快捷鍵啟動器，用一輪按鍵完成應用啟用與視窗選擇。

- 原生 Swift 實作，回應快、開銷小、干擾低
- 支援左/右 Command（0 延遲或自訂延遲）、左/右 Option（0 延遲或自訂延遲）、Space 觸發（最低 0.2 秒延遲，因此不影響日常輸入）
- 針對高頻工作流程最佳化視窗切換體驗
- 本機優先，預設不依賴雲端行為分析

## 官網

- Zeabur 首頁：https://telunkey.zeabur.app

> [!IMPORTANT]
> 如果始終無法正常訪問 Zeabur，其實您應該不會有使用 TelunKey 的場景；如果您有能力且有耐心解決網路問題，建議一定要試試 TelunKey，我相信它絕對能提升您的效率。

## 介面預覽

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="觸發提示" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome 場景" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="設定介面" src="./images/shezhi.png?v=20260329" width="100%" />

## 系統需求

- macOS 14.0 及以上

## 安裝

已安裝 [Homebrew](https://brew.sh/) 的使用者可以執行：

```bash
brew install --cask telungit/tap/telunkey
```

安裝後，從「應用程式」開啟 TelunKey。

## 更新

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

也可以在應用程式內檢查更新。

## 權限說明

TelunKey 需要以下權限以啟用完整功能：

- 輔助使用：監聽全域鍵盤事件
- 螢幕錄製：產生視窗縮圖

## 隱私

TelunKey 採用本機優先策略，核心資料保留在本機。

## 回饋

- Telegram: https://t.me/telungram
