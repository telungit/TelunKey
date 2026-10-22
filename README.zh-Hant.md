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

無需按住觸發鍵。三指滑動、往返，以及三指或四指的輕點、雙擊與按下點擊，都能綁定快捷鍵、單鍵、滑鼠中鍵或視窗操作；長觸固定用於移屏。所有動作作用於本輪鎖定的滑鼠下視窗，並提供只預覽、不執行的練習模式。

若與系統三指滑動、拖移或輕點查詢衝突，TelunKey 會列出實際開啟的項目並直接跳轉到對應的系統設定頁，返回後自動複查，不會自動修改系統設定。衝突解除前，三指滑動與三指長觸暫不接管，點按仍可單獨使用。

## 長觸移屏

顯示器在左邊、右邊，還是上方？長觸展開與系統排列一致的小地圖，滑到想去的螢幕，抬手就把視窗依可用區域比例移過去。

- 四指長觸即可選屏（一般四指滑動仍歸 macOS）；也支援就緒後的三指，或按住觸發鍵配已啟用的一至三指
- 視窗移入目標顯示器目前顯示的桌面；全螢幕視窗或正在顯示全螢幕應用程式的目標螢幕不參與
- 確認前可隨時滑回；在原屏或空白處抬手、提前放開觸發鍵，或按 Esc 均可取消

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
