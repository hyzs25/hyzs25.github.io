---
layout: post
title: "如何提交代码到github上"
description: "如何提交代码到github上"
category: github
tags: [git github]
---
{% include JB/setup %}

# <div style="background-color:#C7E2F7; width:650px; height:55px; border:1px; text-align:center; padding-top:1px"><h3 style="margin-top:20px; border:0px">怎样提交代码到github上</h3></div>

  <div style="background-color:#f5f5f5; width:650px; height:auto; border:1px">
  <ol style="padding:20px 20px">
  <li>在本地库目录下放置要提交的文件</li>
  <li>cmd中执行命令git add .  (单个文件提交后面为文件名)，若删除文件命令为git rm (要删除的文件名)</li>
  <li>继续执行命令git commit -m "提交的描述"</li>
  <li>执行命令git push -u origin master将本地的内容推到git库中</li>
  <li>执行过程中会要求输入用户名和密码，正确输入后提交即可完成</li>
  </ol>
  </div>
