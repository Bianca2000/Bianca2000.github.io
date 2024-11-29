---
title: "{{ replace .Name "-" " " | title }}"
tags: [{{VALUE:tag？}}]
date: {{ .Date | time.Format "2006-01-02T15:04:05+08:00" }}
draft: false
tags: ["first"]
author: "polarbear"
showToc: true
TocOpen: true
hidemeta: false
description: ""
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---