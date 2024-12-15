---
title: Obsidian使用技巧
tags:
  - Obsidian
date: 2024-12-01 12:41:26
draft: false
---
## 用OB上傳blog

這方面感覺已經有很多博主寫過類似的文章了
比如
-  [obsidian 配合 hugo、cloudflare：让发布博客简单到不可思议](https://lillianwho.com/posts/obsidian-hugo-cloudflare/)  
	使用了Quickadd配合temple快速生成
- [Obsidian + Github + Hugo 一站式笔记发布工作流](https://mlosun.com/blog/obsidian-github-hugo/)  
	這個是用[Enveloppe](https://github.com/Enveloppe/obsidian-enveloppe)
然後透過git插件來自定義快捷鍵上傳或是自己寫一個bat快速上傳就可以了
記得在上傳前把.Obsidian資料夾加入.gitignore
## 用每日筆記寫日記

後來我實在懶得用每次用ctrl+P搜索Qickadd
對我來說按鈕更直觀些
所以乾脆在OB設定了每日筆記直接生成在我的daily裡面，方便多啦
```
---
title:
  "{ NAME }": 
tags: 
date:
  "{ DATE:YYYY-MM-DD HH:mm:ss }": 
draft: false
---
```

![Pasted image 20241203170709](image/Pasted%20image%2020241203170709.png)

## 其他雜七雜八的Ob整理

- 在MD檔案上長按ctrl可以看到縮圖 

```javascript
function greet(name) { console.log(`Hello, ${name}!`); }
```