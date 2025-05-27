---
layout: default
title: ホーム
---

# ブログ

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y年%m月%d日" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul> 