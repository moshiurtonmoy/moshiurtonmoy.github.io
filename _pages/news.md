---
layout: archive
title: "News & Updates"
permalink: /news/
author_profile: true
---

<ul>
  {% for item in site.data.news %}
    <li>
      <b>({{ item.date }})</b> — {{ item.title }} 
      {% if item.doi %}
        - <a href="{{ item.doi }}" target="_blank">[Paper]</a>
      {% endif %}
      {% if item.url %}
        - <a href="{{ item.url }}" target="_blank">[🔗]</a>
      {% endif %}
      <blockquote style="margin: 0; padding: 10px 10px 5px 5px;">{{ item.description }}</blockquote>
    </li>
  {% endfor %}
</ul>


