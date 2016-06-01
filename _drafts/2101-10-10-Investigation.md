---
layout: post
title: 研究内容に関して
category : investigation
---

<iframe src="//www.slideshare.net/slideshow/embed_code/key/AgVuFch8PJUmsB" width="425" height="355" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/anondroid5/ss-48538526" title="研究紹介" target="_blank">研究紹介</a> </strong> from <strong><a href="//www.slideshare.net/anondroid5" target="_blank">Fumihiko Akagi</a></strong> </div>

### 提案手法
バースト検出とバースト検出によるtweet集合からの要約生成との二つに分かれる

 - バースト検出 (Burst Detection) 
 - 要約生成 (Summerizing)

###### バースト検出に関して

本稿では、Aggregation Pyramidを利用する

以下のスライドを参照していただきたい

<iframe src="//www.slideshare.net/slideshow/embed_code/key/duY0RiP7SIr5Y7" width="425" height="355" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/anondroid5/aggregation-pyramid" title="Aggregation pyramid" target="_blank">Aggregation pyramid</a> </strong></div>

データの格納、計算を解析に対して適用することで高速にバーストを検出する

###### 要約生成

久保らの提案した要約手法を利用する

###### 評価指標

Linらの提案したROUGEをTwitter用に応用した修正版ROUGEを用いる

その際N=1として評価を行う

開発が難しいが、常に困難に挑戦していきたいと考えている
