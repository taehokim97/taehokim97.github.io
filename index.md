---
layout: default
title: "홈"
description: "Taeho Kim의 블로그에 오신 것을 환영합니다."
permalink: /
---

# 🚧 공사 중...

이곳은 김태호의 블로그입니다.

## 🔥 최근 글

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="font-size: 0.8em;">({{ post.date | date: "%Y-%m-%d" }})</span>
    </li>
  {% endfor %}
</ul>

