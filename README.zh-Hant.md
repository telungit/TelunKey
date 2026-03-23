# TelunKey

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md)

TelunKey 是一款原生 macOS 快捷鍵啟動器，用一輪按鍵完成應用啟用與視窗選擇。

- 原生 Swift 實作，回應快、開銷小、干擾低
- 支援左/右 Command（0 延遲或自訂延遲）、左/右 Option（0 延遲或自訂延遲）、Space 觸發（最低 0.2 秒延遲，因此不影響日常輸入）
- 針對高頻工作流程最佳化視窗切換體驗
- 本機優先，預設不依賴雲端行為分析

## 官網

- Zeabur 首頁：https://telunkey.zeabur.app

> [!IMPORTANT]
> 如果始終無法正常訪問 Zeabur，其實您可能不具備使用 TelunKey 的場景；如果您有能力且有耐心解決網路問題，建議一定要試試 TelunKey，我相信它能提升您的效率。

## 介面預覽

https://github.com/user-attachments/assets/762f43e0-eac3-4ffa-ba33-f68f720d2627

![觸發提示](./images/datishi.png)
![Chrome 場景](./images/chrome.png)
![設定介面](./images/shezhi.png)

## 系統需求

- macOS 14.0 及以上

## 下載

- 最新版本（DMG）：https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- 所有版本：https://github.com/telungit/TelunKey/releases

## 安裝

1. 下載並開啟 `TelunKey.dmg`
2. 將 `TelunKey.app` 拖到「應用程式」
3. 先不要打開 App，先雙擊 DMG 內的 `一鍵修復.command`
4. 看到修復完成後，再打開 TelunKey
5. 只有腳本執行失敗時，才需要在終端機中手動執行如下命令。

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## 權限說明

TelunKey 需要以下權限以啟用完整功能：

- 輔助使用：監聽全域鍵盤事件
- 螢幕錄製：產生視窗縮圖

## 隱私

TelunKey 採用本機優先策略，核心資料保留在本機。

## 回饋

- Telegram: https://t.me/telungram
