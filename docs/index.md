---
layout: home
title: "Trang chủ blog"
---

# 📚 Danh sách bài viết

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%d/%m/%Y" }}</small>
    </li>
  {% endfor %}
</ul>
