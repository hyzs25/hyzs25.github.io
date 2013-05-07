---
layout: post
title: "如何将本地的文章上传到jekyll"
description: "如何将本地的文章上传到jekyll"
category: jekyll
tags: [jekyll]
---
{% include JB/setup %}

# <div style="background-color:#C7E2F7; width:650px; height:55px; border:1px; text-align:center; padding-top:1px"><h3 style="margin-top:20px; border:0px">如何将本地的文章上传到jekyll</h3></div>

  <div style="background-color:#f5f5f5; width:650px; height:auto; border:1px">
  <ol style="padding:20px 20px">
  <li>cmd进入本地的jekyll目录</li>
  <li>git remote add origin (github库)</li>
  <li>执行rake post命令新建一篇文章，并对文章进行编辑，完成后保存</li>
  <li>git add .</li>
  <li>git commit -m "comment"</li>
  <li>git push -u origin master后上传成功</li>
  </ol>
  </div>