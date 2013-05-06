---
layout: post
title: "怎样新建一个github项目"
description: "怎样新建一个github项目"
category: github
tags: [git github]
---
{% include JB/setup %}

# <div style="background-color:#C7E2F7; width:700px; height:55px; border:1px; text-align:center; padding-top:1px"><h3>怎样新建一个github项目</h3></div>

  <div style="background-color:#f5f5f5; width:700px; height:auto; border:1px">
  <ol style="padding:20px 20px">
  <li>在github的网页上新建一个库</li>
  <li>在本地新建一个文件夹作为master</li>
  <li>进入cmd，进入master目录下执行命令git init创建本地项目库</li>
  <li>用git remote add origin .....(git库地址)命令建立本地库和git库的连接</li>
  <li>建好连接后可用git remote -v命令查看连接到的git库。如需改变origin，执行git remote rm origin,再add origin一次即可</li>
  <li>在本地库目录下放置要提交的文件</li>
  <li>cmd中执行命令git add .  (单个文件提交后面为文件名)</li>
  <li>继续执行命令git commit -m "提交的描述"</li>
  <li>执行命令git push -u origin master将本地的内容推到git库中</li>
  <li>执行过程中会要求输入用户名和密码，正确输入后提交即可完成</li>
  </ol>
  </div>
