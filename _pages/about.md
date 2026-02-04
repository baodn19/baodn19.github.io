---
permalink: /
title: "Ngoc Bao Dinh"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Computer Science student, minoring in Mathematics at the University of South Florida, working on the intersection of robotics and computer vision. 

I am an undergraduate researcher at the [Embodied Robotics and Autonomy](https://xiaominlin.github.io/) under [Prof. Xiaomin Lin](https://www.linkedin.com/in/xiaomin-lin/)'s mentorship, contributing to building perception systems for edge robotics. During 2025, I was an undergraduate researcher at the [Reality, Autonomy, and Robot Experience (RARE) Lab](https://therarelab.com/) under [Prof. Zhao Han](https://zhaohanphd.com/)'s guidance, working on human-robot interaction and augmented reality research.

Research
======
I'm interested in bridging the gap between perception and motion planning in robotics for applications in precision agriculture. Furthermore, I aspire to optimize intelligent systems so they can operate in resource-limited environments. In the end, I strive to develop affordable and compact robotics systems for agricultural automation.

I'm excited to explore different methods of computer vision that adapt to different needs in agriculture. My current research interest lies in hyperspectral imaging and deep learning for object recognition.

News
======
<div class="news-scroll-box">
  <div class="news-item">
    <span class="news-date">Jan 16, 2026</span>
    <span class="news-content">I was admitted to the ERA Lab.</span>
  </div>
  <div class="news-item">
    <span class="news-date">Jan 13, 2026</span>
    <span class="news-content">Evaluating Dynamic Surface Compensation for Robots with Projected AR was accepted to HRI 2026 Late-Breaking Reports.</span>
  </div>
  <div class="news-item">
    <span class="news-date">Oct 24, 2025</span>
    <span class="news-content">I was interviewed by FOX13 Tampa Bay for my work at the RARE Lab. (<a href="https://www.fox13news.com/news/usf-researchers-develop-ai-robot-tech-could-save-lives-emergencies">short article</a>)</span>
  </div>
</div>

Selected Publications
======
{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.selected %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<style>
/* Tighten the internal spacing of the publication cards */
.publication-flex-row p {
  margin-bottom: 0.2em !important; /* Reduces gap between authors/venue */
}
.publication-flex-row .archive__item-title {
  margin-top: 0 !important;
  margin-bottom: 0.3em !important; /* Reduces gap below title */
}
.publication-flex-row {
  margin-bottom: 1.5em; /* Controls gap between different papers */
}
</style>