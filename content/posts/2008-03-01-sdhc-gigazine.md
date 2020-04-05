---
title: 早くもSDHCは終了? (GIGAZINE)
author: tarof
type: post
date: 2008-03-01T08:44:11+00:00
url: /2008/03/01/sdhc-gigazine/
categories:
  - Note
tags:
  - PC

---
フラッシュメモリの値段もかなり暴落しているわけですが、
  
16GBも1万円を切っちゃったりなんかして。

そんな中で浮上してきた問題が、容量の頭打ち。
  
SDHCカードでは容量の上限が32GBに規定されています。
  
まだ製品が出始めてから2年ぐらいなのに、すでに32GBも発売されてしまっています。
  
さらに大きい容量を、となると、新規格もしくは規格の拡張が必要になるわけです。

ところがここで問題になってくるのはSDHCが採用してる論理フォーマットFAT32。
  
GIGAZINEの記事ではFAT32の最大容量が32GBとか書いてありますが、FAT32自体は2TBまで対応してます。([->Wikipedia][1])
  
で、Windows 2000以降のOSの場合、標準では2GB以上のパーティションの場合FAT32でフォーマットができないので、そこを何とかしないといけないわけですね。
  
果たしてどうなるんでしょうか。

ちなみにこの問題はMemory Stickにも当てはまりますが、Memory Stickはまだ16GBが発表されている最大容量なので、もう少し猶予はありますかね。

([情報元][2])

 [1]: http://ja.wikipedia.org/wiki/File_Allocation_Table#FAT32
 [2]: http://gigazine.net/index.php?/news/comments/20080301_sdhc/