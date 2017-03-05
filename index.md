---
layout: default
title: 最新文章
---
## {{ page.title }}

### 目录
<ul>
{% for post in site.posts %}
　<li>{{ post.date | date_to_string }} 
	<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
	</li>
　　　　{% endfor %}
　　</ul>