---
layout: page
title: "Tech Blog"
permalink: /blog/
---

# Tech Blog

환경 데이터 분석, 파이프라인, 모델링, 인프라 구축 등 기술 관련 글을 아카이브합니다.

{% for post in paginator.posts %}
- {{ post.date | date: "%Y-%m-%d" }} — [{{ post.title }}]({{ post.url }})  
  {{ post.summary | default: post.excerpt }}
{% endfor %}
