---
layout: default
title: "전체 글 목록"
description: "지금까지 작성한 모든 글들을 모아보세요."
permalink: /posts/
---

# 🗂 전체 포스트 목록

{% for post in site.posts %}
- 📌 **[{{ post.title }}]({{ post.url }})**  
  <small>{{ post.date | date: "%Y-%m-%d" }} | {{ post.tags | join: ", " }}</small>
{% endfor %}