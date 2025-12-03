---
layout: page
title: "Projects"
permalink: /projects/
---

# Projects

환경데이터전략센터에서 수행한 주요 프로젝트입니다.

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})  
  {{ project.summary | default: project.excerpt }}
{% endfor %}
