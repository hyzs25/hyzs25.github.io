---
layout: post
title: "git常用命令"
description: "git常用命令"
category: git
tags: [git]
---
{% include JB/setup %}

# <div style="background-color:#C7E2F7; width:650px; height:55px; border:1px; text-align:center; padding-top:1px"><h3 style="margin-top:20px; border:0px">git常用命令</h3></div>

  <div style="background-color:#f5f5f5; width:650px; height:auto; border:1px">
  <ul style="padding:20px 20px">
  <li>git本地库初始化配置：git init 在本地建一个git库</li>
  <li>git和远程github建立连接：git remote add origin http://-----------.git git remote -v用来查看当前origin的库名，若要移除连接的话执行git remote rm origin </li>
  <li>将当前目录更改或增加的文件加入到git索引中，用git add 命令，若为全部目录用git add . ，若为某个文件用git add 文件名，若要删除文件，用git rm 文件目录/文件名</li>
  <li>提交当前目录所修改的内容用git commit -m "message"</li>
  <li>将本地commit的内容更新到github远程库中，git push -u origin master</li>
  <li>从服务器的仓库中获取代码，和本地代码合并：git pull</li>
  <li>将远程代码库的代码拷贝到本地的目录中：git clone 远程库地址 本地目录</li>
  </ul>
  </div>
