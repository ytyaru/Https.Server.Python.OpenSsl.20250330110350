[en](./README.md)

# Https.Server.Python.OpenSsl

　PythonとopensslコマンドでHTTPSサーバを立てる。

# デモ

* [デモ](https://ytyaru.github.io/Https.Server.Python.OpenSsl.20250330110350/)

# 特徴

* スクリプトを実行するだけでHTTPSサーバが起動する

# 動作要件

* Linux（Raspberry PI OS）
* Pythonインストール済み
* `openssl`コマンドあり
* ブラウザ（Chrome 92）

# 開発環境

* <time datetime="2025-03-30T11:03:35+0900">2025-03-30</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspberry Pi OS](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2020-08-20 <small>[setup](http://ytyaru.hatenablog.com/entry/2020/10/06/111111)</small>
* bash 5.0.3(1)-release
* Python 3.10.5

```sh
$ uname -a
Linux raspberrypi 5.10.103-v8+ #1529 SMP PREEMPT Tue Mar 8 12:26:46 GMT 2022 aarch64 GNU/Linux
```

# インストール

```sh
git clone https://github.com/ytyaru/Https.Server.Python.OpenSsl.20250330110350
```

# 使い方

```sh
cd Https.Server.Python.OpenSsl.20250330110350/docs
./server.sh
```

　ブラウザが起動する。もし起動しないなら手動で起動しURL欄に`https://localhost/`を入力してアクセスする。

　ブラウザによって警告が出るので解除する。以下はChromium 92の場合。

1. 警告画面が出る
2. `詳細設定`ボタンを押す  ![0][]
3. `localhost にアクセスする（安全ではありません）`リンクをクリックする  ![1][]
4. HTTPSサーバが起動し結果表示される  ![2][]
5. サーバを終了させるには起動させた端末上で`Ctrl`+`C`キー押下する

[0]:docs/asset/image/browser-0.png
[1]:docs/asset/image/browser-1.png
[2]:docs/asset/image/browser-2.png

# 注意

* URLやポート番号など詳細はコード参照

# 著者

　ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![twitter](http://www.google.com/s2/favicons?domain=twitter.com)](https://twitter.com/ytyaru1 "twitter")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# ライセンス

　このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

