---
layout: post
title: 改版GitPage的歷程記錄(未寫完)
date: 2018/6/28
description: 針對此Git Page Blog，取用的樣版資源，並針對特定項目修改. # Add post description (optional)
img: md-info1.png # Add image post (optional)
tags: [客製Blog,未寫完] # add tag
#網站參數:{{site.baseurl}}
#圖檔：../assets/img/
#圖檔：../assets/postimg/.png
---
## 相關資源


## 錯誤及需求的修正
### 1.Tag清單頁面它的Url位址不正確
Tag的頁面網址： https://hougii.github.io/blogger/tags
#### 錯誤圖
![錯誤圖](../assets/postimg/2018-06-28_17-34-53.png)

#### 修正方式
修改第一層的 tag.html
將原設定資訊
```html
        <span><a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></span>
```
再加上 site.baseurl資訊
```html
        <span><a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></span>
```

(未寫完)
