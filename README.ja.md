<div align="center">

<img src="./images/icon.png" width="112" alt="TelunKey アイコン" />

# TelunKey

**キーボードでウインドウへ直行、ジェスチャで配置**

キーをひとつ押したまま 1〜2 文字打てば、どの App のどのウインドウへも直行。トラックパッドをひと振りすれば、ウインドウが収まります。

[![最新リリース](https://img.shields.io/github/v/release/telungit/TelunKey?label=release)](https://github.com/telungit/TelunKey/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-black?logo=apple)

[公式サイト](https://www.telunkey.shop) · [インストール](#install) · [フィードバック](#feedback)

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | 日本語 | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

</div>

## 2〜3 キーで App へ直行

トリガーキー（左右の Command、左右の Option、または Space）を押したまま 1〜3 文字を入力します。App が起動していなければ開き、ウインドウがひとつならそのまま前面へ、複数あればピッカーを表示します。押している間はすべての割り当てが一覧表示されるので、覚える必要はありません。

<img src="./images/en/hint.png" width="100%" alt="トリガーキーを押している間に割り当てを一覧表示するヒントメニュー" />

## ひと目でウインドウを選ぶ

ピッカーは App のすべてのウインドウをサムネイルで並べます。数字か文字のキーひとつで選択、Space で直近に使ったウインドウへ。複数のデスクトップに分かれていれば、カードにデスクトップ番号が表示されます。

<img src="./images/en/picker.png" width="100%" alt="サムネイル付きのウインドウピッカー" />

## トラックパッドをひと振りで配置

- **トリガージェスチャ**：トリガーキーを押したままトラックパッドをスワイプし、ポインタの下のウインドウを半分、4 分の 1、または最大化に配置。
- **グローバルジェスチャ**：3 本指のスワイプ、タップ、押し込みに、ウインドウ操作、キーボードショートカット、単一キーを割り当て。
- **ディスプレイをまたぐ**：グローバルジェスチャを端の外まで滑らせると、比率を保ったまま別のディスプレイへ移動。
- どのジェスチャも割り当てを変更でき、実行せずにプレビューだけする練習モードも用意。

<p align="center"><img src="./images/en/gestures.png" width="380" alt="トリガージェスチャ設定" /></p>

## ネイティブで軽量

純粋な Swift 製でサードパーティ依存なし、メニューバーに常駐します。設定は Mac 内に保存され、読み込み・書き出しが可能。インターフェイスは 12 言語に対応しています。

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<a id="install"></a>

## はじめる

macOS 14 以降と [Homebrew](https://brew.sh/) が必要です：

```bash
brew install --cask telungit/tap/telunkey
```

初回起動時にセットアップガイドが表示され、権限、トリガーキー、ショートカット、ジェスチャの設定を案内します。アップデートは App 内から、または次のコマンドで：

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

## 権限とプライバシー

| 権限 | 用途 |
| --- | --- |
| アクセシビリティ（必須） | トリガーキーとジェスチャの検出、ウインドウの切り替えと配置 |
| 画面収録（任意） | ウインドウのサムネイル。未許可でも App アイコンを表示し、切り替えは可能 |

設定は Mac 内に、ライセンス情報はキーチェーンに保存されます。TelunKey がネットワークに接続するのはライセンスの確認とアップデートの確認時のみで、利用データは収集しません。

## 無料版とライセンス

無料版では 5 つまで App を割り当てられ、そのほかの機能はすべて使えます。[公式サイト](https://www.telunkey.shop)で永久ライセンスを購入すると制限がなくなります。

<a id="feedback"></a>

## フィードバック

- [GitHub Issues](https://github.com/telungit/TelunKey/issues)
- [Telegram](https://t.me/telungram)
