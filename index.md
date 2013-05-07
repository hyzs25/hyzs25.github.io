---
layout: page
title: 贺洋的blog
tagline: 不能则学，不知则问。
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## <div style="background-color:#3C84BF; border:1px solid; font-family:微软雅黑, 'Microsoft YaHei'; padding-left:15px;"><h4 style="color:#fff">===文章列表===</h4></div>
<div style="background:#ECECEC; width:700px; display:block padding:0">
<ul class="posts" style="list-style:none; padding:0; margin:0">
  {% for post in site.posts %}
    <li style="height:30px; border-bottom:1px dotted #9B47F2; padding:0; line-height:33px;"><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>
## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


