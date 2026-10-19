<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 圖示" />

# TelunKey

**macOS 視窗切換 · 鍵盤與觸控式軌跡板**

按住觸發鍵，一到三個鍵直達應用程式與視窗；觸控式軌跡板一滑，把視窗擺好。

[![最新版本](https://img.shields.io/github/v/release/telungit/TelunKey?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[官網](https://www.telunkey.shop) · [安裝](#install) · [意見回饋](#feedback)

[简体中文](./README.md) | 繁體中文 | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## 按鍵直達

按住觸發鍵（左 / 右 Command、左 / 右 Option 或空白鍵），輸入綁定的一到三個鍵。應用程式未執行時會開啟；只有一個視窗時直接聚焦；有多個視窗時顯示選擇器。按住觸發鍵期間可查看全部綁定。

<img src="./images/zh/hint.png" width="100%" alt="按住觸發鍵後列出全部綁定的提示選單" />

## 鍵位選擇器

選擇器依鍵盤配置排列視窗縮圖：1–0、Q–P、A–L、Z–M，每頁最多 36 個視窗。按對應的數字或字母鍵選擇。

- 空白鍵：回到最近用過的那個視窗
- 其他桌面的視窗會標出所在桌面
- [ 和 ] 翻頁，Esc 取消，也可以直接點

<img src="./images/zh/picker.png" width="100%" alt="視窗選擇器" />

## 觸發手勢

按住觸發鍵，在觸控式軌跡板上以雙指滑動，可將指標下的視窗放到半螢幕、四分之一螢幕或最大化。

- 上下左右：半螢幕；四個斜向：四分之一螢幕
- 不抬手先上再下：最大化，保留選單列和 Dock
- 滑進取消區就取消，滑回來還能重選

### 三指全域手勢

開啟後，三指的八個方向、往返、輕點、點兩下、長觸與按下，每一種都能綁定組合快速鍵、單鍵、滑鼠中鍵或視窗操作。

- 預設關閉；與系統三指手勢衝突時，設定頁會逐項列出並給出入口
- 跨顯示器：三指全域手勢滑過取消區後繼續向外滑，可將視窗移到另一台顯示器，並保留視窗比例。
- 每個手勢都能重新對應，並附有只預覽、不執行的練習模式。

<p align="center"><img src="./images/zh/gestures.png" width="380" alt="觸發手勢設定頁" /></p>

## 執行與設定

純 Swift 撰寫，沒有第三方相依套件，常駐選單列。設定儲存在本機，可匯入匯出；介面支援 12 種語言。

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## 快速上手

需要 macOS 14 以上，並已安裝 [Homebrew](https://brew.sh/)：

```bash
brew install --cask telungit/tap/telunkey
```

首次開啟會有引導，帶你完成權限、觸發鍵、快速鍵與手勢設定。之後可在應用程式內更新，或執行：

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## 權限與隱私

| 權限 | 用途 |
| --- | --- |
| 輔助使用（必要） | 監聽觸發鍵與手勢，切換、調整視窗 |
| 螢幕錄製（選用） | 產生視窗縮圖；未授予時顯示應用程式圖示，切換不受影響 |

TelunKey 採本機優先策略，不收集鍵盤輸入內容或視窗行為遙測資料。

Dodo Payments 處理付款、購買信箱、授權碼與裝置啟用記錄；啟用時會傳送授權碼及裝置名稱，以管理兩台裝置的名額。授權碼與本機記錄保存在系統鑰匙圈。TelunKey 不儲存銀行卡資訊，使用時無需註冊網站帳號。

## 免費版與永久更新計畫

免費版最多綁定 5 個應用程式，全部功能可用，不限使用時間，無需註冊。永久更新計畫一次付費 US$3.99，不限綁定數量，包含後續更新。

完成支付後查收 Dodo Payments 寄來的授權碼郵件，在 TelunKey 設定的「授權」頁輸入即可，無需註冊帳號。可在 2 台 Mac 上使用；換機前先在舊裝置上解除綁定。

[方案與條款](https://www.telunkey.shop/zh-hant/terms)

<a id="feedback"></a>

## 意見回饋

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
