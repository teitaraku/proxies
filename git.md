git
===

下記コマンドで設定ファイルを書き換える

```bash
$ git config --global -e
```

追加する内容

```
[http]
        proxy = http://proxy.sample.com:8080
[https]
        proxy = http://proxy.sample.com:8080
```
