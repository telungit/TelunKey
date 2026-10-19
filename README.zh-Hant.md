<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 圖示" />

# TelunKey

**鍵盤直達視窗，手勢擺放視窗**

按住一個鍵，敲一兩個字母，直達任何 App 的任何視窗；觸控式軌跡板一滑，視窗就位。

[![最新版本](https://img.shields.io/github/v/release/telungit/TelunKey?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[官網](https://www.telunkey.shop) · [安裝](#install) · [意見回饋](#feedback)

[简体中文](./README.md) | 繁體中文 | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## 兩三個鍵，直達 App

按住觸發鍵（左 / 右 Command、左 / 右 Option 或空白鍵），輸入一到三個字母：App 沒開就打開，只有一個視窗就直接聚焦，有多個視窗就跳出選擇器。按住期間會列出全部綁定，不必死記。

<img src="./images/zh/hint.png" width="100%" alt="按住觸發鍵後列出全部綁定的提示選單" />

## 一眼選中視窗

選擇器以縮圖列出 App 的所有視窗，按數字或字母鍵一鍵選中，空白鍵回到最近使用的那個。視窗分散在多個桌面時，卡片會標出所在桌面。

<img src="./images/zh/picker.png" width="100%" alt="帶縮圖的視窗選擇器" />

## 觸控式軌跡板一滑，視窗就位

- **觸發手勢**：按住觸發鍵在觸控式軌跡板上滑動，把指標下的視窗擺到半螢幕、四分之一螢幕或最大化。
- **全域手勢**：三指滑動、輕點或按下，可綁定視窗操作、快速鍵或單一按鍵。
- **跨顯示器**：全域手勢一路滑出邊緣，視窗按比例移到另一台顯示器。
- 每個手勢都能重新對應，並附有只預覽、不執行的練習模式。

<p align="center"><img src="./images/zh/gestures.png" width="380" alt="觸發手勢設定頁" /></p>

## 原生、輕量

純 Swift 撰寫，沒有第三方相依套件，常駐選單列。設定儲存在本機，可匯入匯出；介面支援 12 種語言。

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## 快速上手

需要 macOS 14 以上，並已安裝 [Homebrew](https://brew.sh/)：

```bash
brew install --cask telungit/tap/telunkey
```

首次開啟會有引導，帶你完成授權、觸發鍵、快速鍵與手勢設定。之後可在 App 內更新，或執行：

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## 權限與隱私

| 權限 | 用途 |
| --- | --- |
| 輔助使用（必要） | 監聽觸發鍵與手勢，切換、調整視窗 |
| 螢幕錄製（選用） | 產生視窗縮圖；未授予時顯示 App 圖示，切換不受影響 |

設定儲存在本機，授權憑證存放在鑰匙圈。TelunKey 只在驗證授權與檢查更新時連網，不收集使用資料。

## 免費與授權

免費版可綁定 5 個 App，其餘功能完整可用；在[官網](https://www.telunkey.shop)購買永久授權後不限數量。

<a id="feedback"></a>

## 意見回饋

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
