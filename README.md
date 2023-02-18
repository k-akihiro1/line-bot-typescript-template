# line-bot-typescript-template

LINE Bot + TypeScript + Firebase Functions のテンプレート
オウム返しボットです。

## 初期設定

1. .firebaserc ファイルを設定
2. .env.expample をもとに.env ファイルを作成&設定

## デプロイ

実行環境

```bash
node 16
```

コマンド

```bash
firebase deploy
or
firebase deploy --only functions:lineBot
```
本番用
https://asia-northeast1-lac-test-2e502.cloudfunctions.net/lineBot

テスト用
(無課金)https://ce41-114-150-114-18.jp.ngrok.io/lac-test-2e502/asia-northeast1/lineBot

https://fe8d651ae78e.jp.ngrok.io/lac-test-2e502/asia-northeast1/lineBot
