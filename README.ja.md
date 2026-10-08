# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey は、1 つのキー操作フローでアプリ起動とウィンドウ選択を完了できる、ネイティブ macOS ショートカットランチャーです。

- ネイティブ Swift 実装により、高速応答・低負荷・低干渉を実現
- 左右 Command（0 遅延またはカスタム遅延）、左右 Option（0 遅延またはカスタム遅延）、Space トリガー（通常入力を妨げない最小 0.2 秒遅延）をサポート
- 高頻度ワークフロー向けにウィンドウ切替体験を最適化
- ローカルファースト設計で、デフォルトではクラウド行動分析に依存しません

## 公式サイト

- Zeabur ホームページ：https://telunkey.zeabur.app

> [!IMPORTANT]
> Zeabur にどうしてもアクセスできない場合、おそらく TelunKey を活用できる場面はないかもしれません。もしネットワーク環境の課題を解決する手段と根気をお持ちであれば、ぜひ TelunKey を試してみてください。作業効率が飛躍的に向上することを確信しています。

## 画面プレビュー

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="トリガーヒント" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome シーン" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="設定画面" src="./images/shezhi.png?v=20260329" width="100%" />

## システム要件

- macOS 14.0 以降

## インストール

[Homebrew](https://brew.sh/) をインストール済みの場合は、以下を実行してください：

```bash
brew update
brew install --cask telungit/tap/telunkey
```

インストール後、「アプリケーション」から TelunKey を起動します。

## アップデート

```bash
brew update
brew upgrade --cask --greedy telungit/tap/telunkey
```

アプリ内からアップデートを確認することもできます。

## 権限について

TelunKey の全機能を利用するには、以下の権限が必要です。

- アクセシビリティ：グローバルキーボードイベントの監視
- 画面収録：ウィンドウサムネイルの生成

## プライバシー

TelunKey はローカルファースト方針を採用しており、主要データは端末内に保持されます。

## フィードバック

- Telegram: https://t.me/telungram
