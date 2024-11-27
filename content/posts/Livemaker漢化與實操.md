---
title: "Livemaker漢化與實操"
date: 2024-11-27T19:29:11+08:00
description: ""
tags: ['Livemaker']
draft: false
toc: true
---
>  近期連續接觸了挺多Livemaker遊戲，趁著記憶還新鮮，趕緊紀錄一下
## 安裝pylivemaker
```
pip install pylivemaker
```
然後你可以去它的[文檔](https://pylivemaker.readthedocs.io/en/latest/usage.html)看，有非常細緻的解釋一些常規操作

## 解包Livemaker

### GARbro
GARbro非常簡單，你只需要把你把你資料夾底下最大的遊戲檔(ex:game.dat/game.exe)丟進去，就能看到一堆0000xxxlsb或是日文的...ㄗㄨ
### Translator++

## 導出csv
這部分你可以直接使用
```
lmlsb extractcsv --encoding=utf-8-sig 00000079.lsb 00000079.csv
```

[Translator++](https://github.com/zyf722/TranslatorPlusPlusChineseWiki)