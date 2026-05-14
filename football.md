---
layout: page
title: 足球分析
subtitle: 交易者视角看绿茵场
---

{% for post in site.categories.football %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%Y年%-m月%-d日" }}
{% endfor %}
