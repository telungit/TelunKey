# TelunKey

[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md)

TelunKey は、1 つのキー操作フローでアプリ起動とウィンドウ選択を完了できる、ネイティブ macOS ショートカットランチャーです。

- ネイティブ Swift 実装により、高速応答・低負荷・低干渉を実現
- 左右 Command（0 遅延またはカスタム遅延）、左右 Option（0 遅延またはカスタム遅延）、Space トリガー（通常入力を妨げない最小 0.2 秒遅延）をサポート
- 高頻度ワークフロー向けにウィンドウ切替体験を最適化
- ローカルファースト設計で、デフォルトではクラウド行動分析に依存しません

## 公式サイト

- Zeabur ホームページ：https://telunkey.zeabur.app

> [!IMPORTANT]
> Zeabur に常にアクセスできない場合、現在の環境では TelunKey が適さない可能性があります。ネットワーク問題を解決できる場合は、TelunKey を試す価値があります。

## 画面プレビュー

https://github.com/user-attachments/assets/762f43e0-eac3-4ffa-ba33-f68f720d2627

![トリガーヒント](./images/datishi.png)
![Chrome シーン](./images/chrome.png)
![設定画面](./images/shezhi.png)

## システム要件

- macOS 14.0 以降

## ダウンロード

- 最新版（DMG）：https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- すべてのバージョン：https://github.com/telungit/TelunKey/releases

## インストール

1. `TelunKey.dmg` をダウンロードして開く
2. `TelunKey.app` を「アプリケーション」にドラッグ
3. インストール後、DMG 内の `一键修复.command` をダブルクリック（下記コマンドを自動実行）：

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

4. スクリプトが失敗した場合のみ、ターミナルで下記コマンドを手動実行
5. TelunKey を再起動

## 権限について

TelunKey の全機能を利用するには、以下の権限が必要です。

- アクセシビリティ：グローバルキーボードイベントの監視
- 画面収録：ウィンドウサムネイルの生成

## プライバシー

TelunKey はローカルファースト方針を採用しており、主要データは端末内に保持されます。

## フィードバック

- Telegram: https://t.me/telungram
