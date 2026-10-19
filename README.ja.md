<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey アイコン" />

# TelunKey

**macOS のウインドウ切り替え · キーボードとトラックパッド**

トリガーキーを押したまま 1〜3 キーでアプリとウインドウへ。トラックパッドをひと払いして配置まで。

[![最新リリース](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[telunkey.shop](https://www.telunkey.shop)

[インストール](#install) · [フィードバック](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | 日本語 | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## キーで直行

トリガーキー（左右の Command、左右の Option、または Space）を押したまま、アプリに割り当てた 1〜3 個のキーを入力します。アプリが起動していなければ開き、ウインドウがひとつなら前面に表示し、複数ならセレクタを表示します。トリガーキーを押している間は割り当ての一覧を確認できます。

<img src="./images/en/hint.png" width="100%" alt="トリガーキーを押している間に割り当てを一覧表示するヒントメニュー" />

## キー配置セレクタ

セレクタではウインドウのサムネイルをキーボード順（1–0、Q–P、A–L、Z–M）に並べ、1 ページに最大 36 個表示します。対応する数字や文字のキーで選択します。

- スペース：最後に使ったウインドウへ
- 別のデスクトップにあるウインドウはそのデスクトップを表示
- [ と ] でページ送り、Esc でキャンセル、クリックでも選べます

<img src="./images/en/picker.png" width="100%" alt="ウインドウセレクタ" />

## トリガージェスチャー

トリガーキーを押したままトラックパッドを 2 本指でスワイプし、ポインタの下のウインドウを半分、4 分の 1、または最大化して配置します。

- 上下左右：半分。斜め 4 方向：4 分の 1
- 指を離さず上から下へ：最大化（メニューバーと Dock は残す）
- キャンセル領域に入ればキャンセル、戻せば選び直し

### 3 本指グローバルジェスチャー

オンにすると、3 本指の 8 方向スワイプ、往復、タップ、ダブルタップ、長押し、押し込みのそれぞれに、ショートカット、単一キー、中クリック、ウインドウ操作を割り当てられます。

- 初期状態はオフ。システムの 3 本指ジェスチャーと競合する場合は、設定画面に一覧と設定への入口を表示
- ディスプレイ間の移動：3 本指ジェスチャーでキャンセル領域を越えて外側へスワイプし続けると、比率を保ったままウインドウを別のディスプレイへ移動できます。
- どのジェスチャも割り当てを変更でき、実行せずにプレビューだけする練習モードも用意。

<p align="center"><img src="./images/en/gestures.png" width="380" alt="トリガージェスチャ設定" /></p>

## 動作と設定

純粋な Swift 製でサードパーティ依存なし、メニューバーに常駐します。設定は Mac 内に保存され、読み込み・書き出しが可能。インターフェイスは 12 言語に対応しています。

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## はじめる

macOS 14 以降と [Homebrew](https://brew.sh/) が必要です：

```bash
brew install --cask telungit/tap/telunkey
```

初回起動時にセットアップガイドが表示され、権限、トリガーキー、ショートカット、ジェスチャの設定を案内します。アップデートはアプリ内から、または次のコマンドで：

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## 権限

| 権限 | 用途 |
| --- | --- |
| アクセシビリティ（必須） | トリガーキーとジェスチャの検出、ウインドウの切り替えと配置 |
| 画面収録（任意） | ウインドウのサムネイル。未許可でもアプリアイコンを表示し、切り替えは可能 |

<a id="feedback"></a>

## フィードバック

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
