---
title: rss訂閱lofter合集文章導入到obsidian
tags:
  - Obsidian
  - 同人
  - rss
  - lofter
date: 2024-12-15T19:37:02+08:00
draft: false
showToc: true
TocOpen: true
UseHugoToc: true
---
## 獲取Lofter合集Rss

### 由Rsshub 獲取 Lofter合集訂閱
以合集ID為15125782為例，
可以在rsshub得到rss訂閱連結  
 [feat(route): 添加Lofter的合集获取功能](https://github.com/DIYgod/RSSHub/pull/16732#top)  

感覺最近Rsshub的主伺服器有點不堪重負，可以試試別的[公共實例](https://docs.rsshub.app/guide/instances)
如此就能得到以下連結
```
 https://rsshub.henry.wang/lofter/collection/15125782?limit=200
 //這裡面?limit=200是為了強制顯示超過十條以上的文章
```

這時候你其實就可以隨便用任何RSS閱讀器觀看了，但我有一個夢想，
就是能在本地看lofter而不是用RSS閱讀器直接提取網頁框架

## 匯入Obsidian

### 下載[obsidian-rss-copyist](https://github.com/aoout/obsidian-rss-copyist)

這個插件的作者真是我的心靈摯友，不用造輪子就能免費用，真的是非常美好的事情。
進入項目介紹，其實都寫得很清楚，操作如下：

- Obsidian裡面新建一個放rss的資料夾，我命名為rss
- 在rss下新建兩個.md，一個一定要叫template，另一個放你的rss連結、可以叫合集名稱
  > 血的教訓，我之前把 template 亂命名，就不能運作
  > ![Pasted%20image%2020241215210408.png](image/Pasted%20image%2020241215210408.png)
- ctrl+P找到rss的命令行`Get the newest articles from all feeds`就能運作了

*如此就能快速把文章下載成md，對本地儲存強迫症不要太好了。*

![Pasted%20image%2020241215210840.png](image/Pasted%20image%2020241215210840.png)