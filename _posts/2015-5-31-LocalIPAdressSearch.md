---
layout: post
title: ローカルIPアドレスを持ってる人を調べる
category : learning
tagline: "Network"
tags : [Network]
---

同じネットワーク上に存在する（使用している）PCのIPアドレスを調べる方法（確認）

### OS

Windows 7

 MS-DOS

cmd（コマンドプロンプト） => Windows key + R key でも同様

「スタート」メニューから「ファイル名を指定して実行」をクリック

「名前」欄のテキストボックスに

cmd

と入力し「OK」ボタンをクリック

「コマンドプロンプト」が起動するので

    for /l %i in (0,1,255) do ping -w 1 -n 1 192.168.24.%i && arp -a 192.168.24.%i >> ping.log

「ping.log」の欄を確認する

※「192.168.24.%i」の部分は自分の環境に合わせて書き換える
