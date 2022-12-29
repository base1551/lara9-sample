# lara9-sample

## 概要
Laravel9のサンプルプロジェクトです。

## 環境構築
`$cd [cloneしたプロジェクト]`\
makefileに実行コマンドを記載しています。以下コマンドを実行してください。\
`$ make install`

## DBクライアントツールで接続したい場合
- dbのportは3306で設定しています
- その他の設定は`.env`記載の通り接続ください
- portを変更したい場合は、`docker-compose.yml`のdbのport行でportを変更して、コンテナを再起動してください

## その他
環境構築は以下のサイトを参考にしています。
https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4#%E8%A3%9C%E8%B6%B3mysql%E3%82%AF%E3%83%A9%E3%82%A4%E3%82%A2%E3%83%B3%E3%83%88%E3%83%84%E3%83%BC%E3%83%AB%E3%81%A7%E6%8E%A5%E7%B6%9A%E3%81%97%E3%81%9F%E3%81%84
