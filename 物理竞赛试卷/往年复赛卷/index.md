---
layout: page
title: 往年复赛卷
permalink: /物理竞赛试卷/往年复赛卷/
---

# 往年复赛卷

物理竞赛复赛历年真题。

{% assign files = site.static_files | where: path, /物理竞赛试卷/往年复赛卷/ %}
{% for file in files %}
- [{{ file.name }}]({{ file.path }})
{% endfor %}

> 资料链接待填入
