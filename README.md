# What
ローカルでNginxを試すための設定

# 使い方
起動方法
```terminal
$ docker-compose up
```

8080ポートでNginxの動作を確認できる。

用意したページは、/, /test, /testingの3つ

conf.d以下にファイルを追加したり、default.confを触ったりして、動作確認できる。
