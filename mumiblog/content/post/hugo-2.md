---
title: "使用Hugo 發布靜態網站 - 2"
date: 2023-04-13T00:00:28+08:00
tags: ["hugo"]
draft: false
---

接續上篇，這篇文章主要是分享自己的心得經驗，一開始看到 "Creating a Blog with Hugo and Github in 10 minutes"，
想說自己也能快速的建立blog，但實際上並沒有...

    
    有想要跟著做的人，可以搭配影片，與我下面的說明一起看
 
* github.io的subdomain要與username相同<br>  
    例如: 我自己的就要是WebZaiMumi.github.io，config.toml的baseURL也同樣要是這個

* 影片中的產生新文章的資料夾名稱與theme有關<br>  
    影片中使用contrast-hugo
          對應到的就會是hugo new posts/mypost.md<br>  
          我使用的是hugo-theme-stack
          對應到的就會是hugo new post/mypost.md

* 部屬是需要時間的，並不像影片可以秒做完<br>  
    你可以去github.io的action，確認是否已成功build & depoly



參考資料:

https://www.youtube.com/watch?v=LIFvgrRxdt4



