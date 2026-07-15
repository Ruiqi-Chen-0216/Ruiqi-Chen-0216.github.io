---
permalink: /
title: ""
excerpt: ""
author_profile: false
layout: default
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<div class="home-top">

<div class="home-profile-card">
  <img src="{{ site.author.avatar | absolute_url }}" class="home-avatar" alt="{{ site.author.name }}">
  <div class="home-profile-info">
    <h2 class="home-name">{{ site.author.name }}</h2>
    <p class="home-incoming">Incoming Ph.D. in <a href="https://cse.engin.umich.edu/">Computer Science and Engineering</a></p>
    <p class="home-university">University of Michigan</p>
    <div class="home-labs">
      <a href="https://guoanhong.com/">Human-AI Lab</a>
    </div>
    <hr class="home-divider">
    <div class="home-links">
      {% if site.author.location %}<span class="home-link-static"><i class="fas fa-fw fa-map-marker-alt"></i><span>{{ site.author.location }}</span></span>{% endif %}
      {% if site.author.email %}<a href="mailto:{{ site.author.email }}"><i class="fas fa-fw fa-envelope"></i><span>ruiqich [at] umich [dot] edu</span></a>{% endif %}
      {% if site.author.googlescholar %}<a href="{{ site.author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i><span>Google Scholar</span></a>{% endif %}
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}"><i class="fab fa-fw fa-github"></i><span>{{ site.author.github }}</span></a>{% endif %}
      {% if site.author.linkedin %}<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}"><i class="fab fa-fw fa-linkedin"></i><span>Ruiqi Chen</span></a>{% endif %}
      {% if site.author.orcid %}<a href="{{ site.author.orcid }}"><i class="ai ai-orcid-square ai-fw"></i><span>0000-0001-7255-5353</span></a>{% endif %}
    </div>
  </div>
</div>

<div class="home-bio" markdown="1">

<span class='anchor' id='about-me'></span>

<div class="notice--info" style="margin-bottom: 1.2em;">
🔍 I am actively looking for <strong>industry research internship opportunities in Summer 2026</strong>. Please feel free to <a href="mailto:{{ site.author.email }}">get in touch</a>!
</div>

I am Ruiqi Chen, an incoming Ph.D. student in [Computer Science and Engineering](https://cse.engin.umich.edu/) at the **University of Michigan**. Previously, I was at the **University of Washington**, where I worked with [Prof. Jon E. Froehlich](https://jonfroehlich.github.io/) in [Makeability Lab](https://makeabilitylab.cs.washington.edu/) and [Prof. Jacob O. Wobbrock](https://faculty.washington.edu/wobbrock/) in [ACE Lab](https://depts.washington.edu/acelab/index.html). I also collaborate closely with [Prof. Aditya Parameswaran](https://people.eecs.berkeley.edu/~adityagp/) at the **University of California, Berkeley**.

My research focuses on building and evaluating AI models and systems that align with human knowledge, goals, and values. More broadly, I am interested in how AI systems can better understand what people know, need, and care about, from agentic data systems and multimodal benchmarks to embodied and human-AI applications.

# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Our paper ***CapNav*** has been accepted to CVPR 2026! Proud to be co-first author on my first CVPR paper.
- *2025.09*: &nbsp;🎉🎉 My research paper developed at UC Berkeley under the supervision of Prof. Aditya Parameswaran has been accepted to CIDR 2026!
- *2025.07*: &nbsp;🎉🎉 Two human-AI research papers ***FlyMeThrough*** and ***SlideAudit*** have been accepted to UIST 2025!

</div>

</div>

# 📝 Publications
( **<sup>*</sup>** means Equal Contribution)

{% include publications-list.html %}
