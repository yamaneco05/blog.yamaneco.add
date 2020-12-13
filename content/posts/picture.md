+++ 
draft = false
date = 2020-11-30T22:57:21+09:00
title = "【hugo】画像を挿入したい"
slug = "picture" 
tags = ["hugo", "picture"]
categories = ["blog"]
+++

### そういやblogなのに、何かが足りない・・

そう。写真！  
まあ、技術ブログ目指しているから（若干方向性は怪しいが）写真なくても全然OKだけど。  
どっちかというと、ないよりはあった方がｲｲﾈ。  
google先生に質問するが、なかなかこれという回答に巡り合えず。  
 

(1)ショートコードを作成 → 失敗  
今度調べてリトライしよう・・・

{{<amp-img src="/img/posts/oni1.jpg" width="16" height="9" layout="responsive">}}


(2)リンクを貼る

```
![代替テキスト](/img/posts/oni1.jpg)
```

これでできた！  

![代替テキスト](/img/posts/oni1.jpg)

娘がipadで描いた作品です・・   
画像の大きさを変えたり、トリミングしたりする方法も調べよう。