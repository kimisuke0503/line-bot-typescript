# LINE Bot by Typescript

## 開発セットアップ

1. パッケージのインストール
   ```console
   yarn
   ```
2. dev server の起動
   ```console
   yarn dev
   ```

## ローカルから外部公開する場合

1. ビルドする

   ```console
   yarn build
   ```

2. ngrokの起動

   ```
   ngrok http 3000
   ```

3. ngrokが発行したURLをLINE Developersに登録（ngrok起動したらコンソールにURL出てくる）
   `https://developers.line.biz/console/channel/2000263929/messaging-api`

   7/30時点(多分毎回変わる。`/webhook`を忘れず)

   ```console
   https://90fc-116-222-225-72.ngrok-free.app/webhook
   ```

## Renderに
