---
layout: archive
title: "News & Updates"
permalink: /news/
author_profile: true
---


{% for item in site.data.news %}
### 📅 {{ item.date }}  
**{{ item.title }}**  
{{ item.short_description }}  

<button onclick="toggleNews('news-{{ forloop.index }}')" class="read-more-btn">Read More</button>  

<div id="news-{{ forloop.index }}" class="news-full-description" style="display: none;">
  {{ item.full_description }}
</div>

---
{% endfor %}


<script>
function toggleNews(id) {
  var element = document.getElementById(id);
  if (element.style.display === "none") {
    element.style.display = "block";
  } else {
    element.style.display = "none";
  }
}
</script>


