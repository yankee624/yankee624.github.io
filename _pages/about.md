---
layout: about
title: about
permalink: /
subtitle: Ph.D. Student, <a href='https://cse.snu.ac.kr/en'>Seoul National University</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Seoul National University</p>
    <p>Seoul, Republic of Korea</p>
    <p>kchg.yang@gmail.com</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

## Research Interest

I am deeply passionate about developing innovative systems, with a particular interest in **Mobile/Edge AI Acceleration** and **eXtended Reality (XR) Systems**. My expertise primarily lies in vision workloads, yet my enthusiasm extends to embracing and mastering new domains. I firmly believe in the power of collaboration to achieve groundbreaking advancements.

## Education

**Ph.D. in Computer Science & Engineering** (2023 ~ Present)
Seoul National University, Seoul, Republic of Korea
*Advisor: Prof. Youngki Lee*

**M.S. in Computer Science & Engineering** (2021 ~ 2023)
Seoul National University, Seoul, Republic of Korea
*Advisor: Prof. Youngki Lee*
**Best Thesis Award** in Computer Science & Engineering Department

**B.S. in Industrial Engineering** (2015 ~ 2021)
Seoul National University, Seoul, Republic of Korea
*Minor in Computer Science & Engineering*
GPA: 4.05/4.30, **Summa Cum Laude** graduation

---

## Publications

{% bibliography %}

---

## Experience

**Applied Scientist Intern** (Jul. 2024 ~ Oct. 2024)
[Amazon](https://www.amazon.com/), California, US
• Efficient On-device Video Understanding with Large Vision Language Models

**Data Science Intern** (Jun. 2019 ~ Aug. 2019)
[SK Hynix](https://www.skhynix.com/), Gyeonggi-do, Republic of Korea
• Deep Learning based DRAM Module Visual Inspection Process
• **Best Project Award**

**Product Manager Intern** (Dec. 2018 ~ Feb. 2019)
Educast, Seoul, Republic of Korea
• Online course development (Linear Algebra for Machine Learning) & Marketing experiments

---

## Projects

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
{% for project in sorted_projects %}
  <div class="project">
    <h3>{{ project.title }}</h3>
    <p class="project-date">{{ project.date }}</p>
    <p>{{ project.description }}</p>
  </div>
{% endfor %}
</div>
