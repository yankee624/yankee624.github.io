---
layout: about
title: about
permalink: /
subtitle: Ph.D. Student, <a href='https://cse.snu.ac.kr/en'>Seoul National University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Seoul, Republic of Korea</p>
    <p>kchg.yang@gmail.com</p>

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

## Research Interest

I am deeply passionate about developing innovative systems, with a particular interest in **Mobile/Edge AI Acceleration** and **eXtended Reality (XR) Systems**. My expertise primarily lies in vision workloads, yet my enthusiasm extends to embracing and mastering new domains. I firmly believe in the power of collaboration to achieve groundbreaking advancements.

## Education

**Ph.D. in Computer Science & Engineering** (2023 ~ Present)<br>
Seoul National University, Seoul, Republic of Korea<br>
*Advisor: Prof. Youngki Lee*

**M.S. in Computer Science & Engineering** (2021 ~ 2023)<br>
Seoul National University, Seoul, Republic of Korea<br>
*Advisor: Prof. Youngki Lee*<br>
**Best Thesis Award** in Computer Science & Engineering Department

**B.S. in Industrial Engineering** (2015 ~ 2021)<br>
Seoul National University, Seoul, Republic of Korea<br>
*Minor in Computer Science & Engineering*<br>
GPA: 4.05/4.30, **Summa Cum Laude** graduation

---

## Publications

{% bibliography %}

---

## Experience

**Applied Scientist Intern** (Jul. 2024 ~ Oct. 2024)<br>
Amazon, California, US<br>
• Efficient On-device Video Understanding with Large Vision Language Models

**Data Science Intern** (Jun. 2019 ~ Aug. 2019)<br>
SK Hynix, Gyeonggi-do, Republic of Korea<br>
• Deep Learning based DRAM Module Visual Inspection Process (Best Project Award)<br>

**Product Manager Intern** (Dec. 2018 ~ Feb. 2019)<br>
Educast, Seoul, Republic of Korea<br>
• *Linear Algebra for Machine Learning* Course Development & Marketing

---

## Projects

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
{% for project in sorted_projects %}
  <div class="project">
    <h3>{{ project.title }}</h3>
    <p>{{ project.description }}</p>
  </div>
{% endfor %}
</div>
