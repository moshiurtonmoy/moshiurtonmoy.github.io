---
layout: archive
title: "News & Updates"
permalink: /news/
author_profile: true
---

📢 Recent News  
===

{% for item in site.data.news %}
### 📅 {{ item.date }}  
**{{ item.title }}**  
{{ item.description }}  
---
{% endfor %}

