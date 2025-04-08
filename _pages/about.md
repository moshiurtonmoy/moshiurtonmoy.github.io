---
permalink: /
title: "Welcome"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a computer science graduate passionate about deep learning and computer vision. My work focuses on developing efficient and trustworthy AI models for medical image analysis and smart agriculture, bridging research with real-world impact.


## 🔬 Research Interests
- Computer Vision
- Responsible and Trustworthy AI
- Biomedical Image Analysis
- Efficient AI

🔗 [See my publications →](/publications/)

## 📢 Recent News  
<ul>
  {% for item in site.data.news limit:10 %}
    <li>
      ({{ item.date }}) — {{ item.title }} 
      {% if item.doi %}
        - <a href="{{ item.doi }}" target="_blank">[Paper]</a>
      {% endif %}
      {% if item.url %}
        - <a href="{{ item.url }}" target="_blank">[🔗]</a>
      {% endif %}
    </li>
  {% endfor %}
</ul>


🔗 [See all updates →](/news/)


