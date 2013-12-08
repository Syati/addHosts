addHosts
========

/etc/hosts に任意の hosts を加える。


利用方法
--------

addHosts 内の以下の*"IP FQDN"* を書き換える。

```sh
hosts=(
    "IP FQDN1"
    "IP FQDN2"
)
```

後は *コマンド* を叩くだけ

コマンド
--------

* 追加
   
```sh
sudo addHosts add
```

* 削除

```sh
sudo addHosts clean
```

その他
--------

hosts.back として、コマンド実行前のファイルが保存される。
