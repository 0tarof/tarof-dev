---
title: SquidとNicoCacheの連携
author: tarof
type: post
date: 2008-10-25T19:43:28+00:00
url: /2008/10/26/squidとnicocacheの連携/
categories:
  - Note
tags:
  - 雑記

---
ニコ厨の方々にはおなじみのNicoCache、当方ではNicoCache_nl(以下nl)を使っています。
  
以前からサーバにはSquidでProxyを立てていて、nlも立てていたわけなんですが、全ての通信をnl経由にすると重くなりますので、プロキシ設定スクリプトとかも使っていたんですが、最近ブラウザをSleipnirに戻したこともあり、「インターネットオプションを使用して接続」したりしなければいけなくなったわけです。
  
そんな時に考えたのが、

> クライアント→Squid→ニコニコ動画のみnl

と言う構成なんですが……。
  
Google先生にsquid.confについて相談しつつ設定してみたんですが上手くいかず、今更ですがさっきふと思いついて[こんな風に][1]聞いてみたら教えてくれました。

sakur@ : [ニコキャッシュ(nicoCache)とsquidの多段プロキシー構成][2]

と言うわけで、この通りに設定したら上手くいきました。
  
3分で……とはいきませんでした。
  
結局Flash10にしたり、flvplayer_wrapperを更新したりもしたので結構時間は食いました。

で、これの何がいいかって、Sleipnirの場合もそうですが、プロキシ設定スクリプトを使えないブラウザでは大いに有効で、まだテストはしていませんがPS3等でも使えるでしょう。

 [1]: http://www.google.com/search?q=squid+NicoCache
 [2]: http://www.sakura.podzone.org/blog/log/eid35.html