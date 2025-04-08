---
layout: archive
title: "News & Updates"
permalink: /news/
author_profile: true
---


<ul class="news-container">
{% for item in site.data.news %}
  <li class="news-item"> <b>({{ item.date }})</b> — {{ item.title }} </li>
{% endfor %}
</ul>

