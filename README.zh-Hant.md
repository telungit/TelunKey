<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey 圖示" />

# TelunKey

**macOS 視窗切換 · 鍵盤與觸控式軌跡板**

按住觸發鍵，一到三個鍵直達應用程式與視窗；觸控式軌跡板一滑，把視窗擺好。

[![最新版本](https://img.shields.io/github/v/release/telungit/TelunKey?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[安裝](#install) · [意見回饋](#feedback)

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

按住觸發鍵，以已啟用的單指、雙指或三指滑動，將游標下的視窗放到半螢幕、四分之一螢幕或最大化。

- 上下左右：半螢幕；四個斜向：四分之一螢幕
- 不抬手先上再下：最大化，保留選單列和 Dock
- 滑進取消區就取消，滑回來還能重選

<p align="center"><img src="./images/zh/gestures.png" width="380" alt="觸發手勢設定頁" /></p>

## 三指與四指全域手勢

無需按住觸發鍵。三指滑動、往返，以及三指或四指的輕點、雙擊與按下點擊，都能綁定快捷鍵、單鍵、滑鼠中鍵或視窗操作。長觸固定用於移屏。 操作作用於本輪鎖定的滑鼠下視窗。

全新安裝預設開啟，升級保留原設定。長觸固定用於移螢幕，其餘手勢可重新對應；練習模式只預覽、不執行。

使用三指滑動與長觸選螢幕前，請先關閉系統三指拖移，並將系統三指水平、垂直滑動改為四指或關閉。TelunKey 只列出實際開啟的衝突項，分別引導前往「觸控式軌跡板 → 更多手勢」及「輔助使用 → 指標控制 → 觸控式軌跡板選項」；返回後自動檢查，也可稍後設定。衝突尚未解決時，三指滑動與長觸暫不接管，點按仍可單獨使用；系統查詢的輕點衝突另行提示。TelunKey 不會自動修改系統設定。

## 長觸移屏

顯示器在左邊、右邊，還是上方？長觸展開與系統排列一致的小地圖，滑到想去的螢幕，抬手再移動視窗。

- 四指先長觸，再滑動選螢幕；也支援完成設定後的三指，或按住觸發鍵使用已啟用的一至三指
- 依顯示器邏輯排列選屏，視窗依兩屏可用區域比例定位
- 確認前可以滑回；在來源螢幕或空白處抬手取消；也可按 Esc 取消。

一般四指滑動仍由 macOS 處理。四指先長觸，成功進入選螢幕後才暫時接管這次手勢，抬手後恢復系統手勢。

只能移到其他顯示器目前顯示的桌面。單屏沒有移入目標；全螢幕視窗不執行，正在顯示全螢幕應用程式的目標螢幕不可選。在來源螢幕、空白或不可用螢幕抬手即取消；觸發手勢須持續按住觸發鍵，提前放開也會取消。

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

## 權限

| 權限 | 用途 |
| --- | --- |
| 輔助使用（必要） | 監聽觸發鍵與手勢，切換、調整視窗 |
| 螢幕錄製（選用） | 產生視窗縮圖；未授予時顯示應用程式圖示，切換不受影響 |

<a id="feedback"></a>

## 意見回饋

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
