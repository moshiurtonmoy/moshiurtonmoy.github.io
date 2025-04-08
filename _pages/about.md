---
permalink: /
title: "Welcome"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a computer science graduate, passionate about advancing deep learning and computer vision with their impactful applications in medical image analysis and smart agriculture. My research focuses on developing lightweight, efficient, and trustworthy deep learning models for real-world applications. My goal is to bridge the gap between AI research and practical deployment, making cutting-edge technology accessible and impactful.

## 🔬 Research Interests
- Computer Vision
- Responsible AI
- Biomedical Image Analysis
- Efficient AI

## 📢 Recent News  
<ul class="news-container">
{% for item in site.data.news limit:5 %}
  <li class="news-item"> <b>({{ item.date }})</b> — {{ item.title }} </li>
{% endfor %}
</ul>

🔗 [See all updates →](/news/)


