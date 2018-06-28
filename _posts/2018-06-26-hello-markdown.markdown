---
layout: post
title: 這是一篇測試新文章-如何寫MD File(未寫完)
date: 2018/6/26
description: Markdown file 的基本語法處理. # Add post description (optional)
img: md-info1.png # Add image post (optional)
tags: [客製Blog,未寫完] # add tag
#網站參數:{{site.baseurl}}
#圖檔：../assets/img/
#圖檔：../assets/postimg/
---

## Markdown的基本語法說明

 基本的表示語法：
![基本語法](../assets/img/md-info1.png "基本查詢語法一")

基本的連結/圖檔的操作寫法
![基本語法](../assets/img/md-info2.png "基本查詢語法二")

基本的表格類使用
![基本語法](../assets/img/md-info3.png "基本查詢語法三")

## 後記心得
今天測試一下，如何透過markdown File 來寫 圖檔資訊。
這流程，沒有Blogger那樣容易加上圖檔

Markdown 寫法
```markdown
![文字](圖源url "Title")
```
最終產生出來的HTMl
```html
<img src ="圖源" alt="文字" title="Title">
```

程式在寫時，還是透過OneNote當作 字典來查詢。

