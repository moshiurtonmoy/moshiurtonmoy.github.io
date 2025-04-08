---
layout: archive
title: "News & Updates"
permalink: /news/
author_profile: true
---

<ul>
  {% for item in site.data.news %}
    <li>
      ({{ item.date }}) — {{ item.title }} 
      {% if item.doi %}
        - <a href="{{ item.doi }}" target="_blank">[Paper]</a>
      {% endif %}
      {% if item.url %}
        - <a href="{{ item.url }}" target="_blank">[🔗]</a>
      {% endif %}
      <p style="margin: 10px; padding: 10px 10px 10px 10px;">{{ item.description }}</p>
    </li>
  {% endfor %}
</ul>


