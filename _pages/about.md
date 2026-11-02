---
permalink: /
title: "Welcome"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

How can we build AI systems that do more than recognize patterns—systems that can reason, adapt, and earn our trust? This question drives my research at the intersection of causality, interpretability, efficiency, and reasoning. I am particularly interested in developing reliable and resource-efficient AI models that address real-world challenges, bridging foundational research and practical applications to create meaningful societal impact.


## 🔬 Research Interests

- Trustworthy and Interpretable AI
- Reinforcement Learning
- Causal AI and Causal Representation Learning
- Neuro-symbolic AI
- Deep Learning and Computer Vision
- AI for Healthcare and Smart Agriculture

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


## 🎓 Education
- MS in Computer Science | Texas A&M University-Kingsville, TX 78363, USA | August 2025 - Present 
  
- BSc in Computer Science and Engineering | University of Asia Pacific, Dhaka, Bangladesh | September 2018 - January 2023  



