# FoofSNS

これは、食べ物系SNS制作のために作られたアプリケーションです。
[@SYOUTYAN_KG](https://bitware-blog.com/)著

## ライセンス

以下にて公開予定
https://bitware-blog.com/

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
その後、次のコマンドで必要になる RubyGems をインストールします。

```
$ bundle install --without production
```

その後、データベースへのマイグレーションを実行します。

```
$ rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ rails test
```

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ rails server
```
