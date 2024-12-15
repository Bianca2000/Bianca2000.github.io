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