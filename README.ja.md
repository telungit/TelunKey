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

トリガーキーを押しながら、有効にした1本・2本・3本指でスワイプし、ポインタ下のウインドウを半分、4分の1、または最大化して配置します。

- 上下左右：半分。斜め 4 方向：4 分の 1
- 指を離さず上から下へ：最大化（メニューバーと Dock は残す）
- キャンセル領域に入ればキャンセル、戻せば選び直し

<p align="center"><img src="./images/en/gestures.png" width="380" alt="トリガージェスチャ設定" /></p>

## 3本指・4本指のグローバルジェスチャー

トリガーキーは不要。3本指のスワイプや往復、3本または4本指のタップ、ダブルタップ、物理クリックに、ショートカット、単一キー、中クリック、ウインドウ操作を割り当てられます。長押しは画面間移動専用です。すべての操作はポインタ下で固定されたウインドウに作用し、実行せずにプレビューできる練習モードも備えています。

システムの3本指スワイプ、ドラッグ、または「調べる」と競合する場合は、有効な項目だけを表示して該当するシステム設定ページへ直接案内し、戻ると自動で再確認します（システム設定を自動で変更することはありません）。競合が解消されるまで3本指スワイプと長押しは動作せず、タップとクリックはそのまま使えます。

## 長押しで画面間移動

左、右、それとも上？長押しで macOS の画面配置に沿ったマップを開き、移動先へスライドして指を離すと、使用可能領域の比率を保ったままウインドウを移動します。

- 4本指の長押しで画面を選択（通常の4本指スワイプは macOS が処理）。設定済みの3本指、またはトリガーキーを押しながら有効な1〜3本指でも使えます
- 移動先ディスプレイで現在表示中のデスクトップへ移動します。フルスクリーンウインドウや、フルスクリーンアプリを表示中のディスプレイは対象外です
- 確定前はいつでも戻れます。元の画面や空白で指を離す、トリガーキーを先に離す、または Esc キーでキャンセルできます

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
