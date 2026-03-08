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
    <p class="home-degree">M.S. in <a href="https://www.hcde.washington.edu/">Human Centered Design &amp; Engineering</a></p>
    <p class="home-university">University of Washington</p>
    <div class="home-labs">
      <a href="https://makeabilitylab.cs.washington.edu/">Makeability Lab</a> &middot; <a href="https://depts.washington.edu/acelab/">ACE Lab</a><br>
      Collab: <a href="https://people.eecs.berkeley.edu/~adityagp/">UC Berkeley</a>
    </div>
    <hr class="home-divider">
    <div class="home-links">
      {% if site.author.email %}<a href="mailto:{{ site.author.email }}"><i class="fas fa-fw fa-envelope"></i> Email</a>{% endif %}
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}"><i class="fab fa-fw fa-github"></i> GitHub</a>{% endif %}
      {% if site.author.googlescholar %}<a href="{{ site.author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i> Scholar</a>{% endif %}
      {% if site.author.linkedin %}<a href="https://www.linkedin.com/in/{{ site.author.linkedin }}"><i class="fab fa-fw fa-linkedin"></i> LinkedIn</a>{% endif %}
      {% if site.author.orcid %}<a href="{{ site.author.orcid }}"><i class="ai ai-orcid-square ai-fw"></i> ORCID</a>{% endif %}
    </div>
  </div>
</div>

<div class="home-bio" markdown="1">

<span class='anchor' id='about-me'></span>

<div class="notice--info" style="margin-bottom: 1.2em;">
🔍 I am actively looking for <strong>industry research internship opportunities in Summer 2026</strong>. Please feel free to <a href="mailto:{{ site.author.email }}">get in touch</a>!
</div>

I am Ruiqi Chen, currently pursuing a Master of Science in  [Human Centered Design & Engineering](https://www.hcde.washington.edu/) at the **University of Washington**, affiliated with [Makeability Lab](https://makeabilitylab.cs.washington.edu/) by [Prof. Jon E. Froehlich](https://jonfroehlich.github.io/) and [ACE Lab](https://depts.washington.edu/acelab/index.html) by [Prof. Jacob O. Wobbrock](https://faculty.washington.edu/wobbrock/). I also collaborate closely with [Prof. Aditya Parameswaran](https://people.eecs.berkeley.edu/~adityagp/) at the **University of California, Berkeley**. Previously, I obtained my Dual B.S. degree in Data Science from Duke University and Duke Kunshan University, where I worked with [Prof. Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en) in [HCI Lab](https://arkxlab.github.io/).

My research lies at the intersection of Human–Computer Interaction (HCI) and Artificial Intelligence (AI), combining human and machine intelligence to **train human-centered AI models** and **build human-centered AI systems**. My work bridges HCI and AI through the design of **AI-assisted tools** that empower rather than replace human intelligence. Over the past four years, my research has spanned human-centered AI, computer vision, large language and vision-language models, and machine learning.

# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Our paper ***CapNav*** has been accepted to CVPR 2026! Proud to be co-first author on my first CVPR paper.
- *2025.12*: &nbsp;🎉🎉 My undergraduate research paper ***GestoBrush*** received the 🏆<span style="color:red; font-weight:bold;">Best Paper Award</span> at ACM VINCI 2025!
- *2025.09*: &nbsp;🎉🎉 My research paper developed at UC Berkeley under the supervision of Prof. Aditya Parameswaran has been accepted to CIDR 2026!
- *2025.07*: &nbsp;🎉🎉 Two human-AI research papers ***FlyMeThrough*** and ***SlideAudit*** have been accepted to UIST 2025!
- *2025.02*: &nbsp;🎉🎉 Two of my undergraduate research works have been accepted to CHI 2025!

</div>

</div>

# 📝 Publications
( **<sup>*</sup>** means Equal Contribution)

<div class="pub-filter">
  <button class="filter-btn active" data-filter="all">All</button>
  <button class="filter-btn" data-filter="benchmark">AI Benchmark</button>
  <button class="filter-btn" data-filter="human-ai">Human-AI</button>
  <button class="filter-btn" data-filter="hci">Human Computer Interaction</button>
</div>

<div class="pub-item" data-categories="benchmark">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/ArXiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Data Agent Benchmark

[Ruiying Ma](https://ruiying-ma.github.io/)<sup>*</sup>,
[Shreya Shankar](https://www.sh-reya.com/)<sup>*</sup>, **Ruiqi Chen**, …, [Aditya G. Parameswaran](https://people.eecs.berkeley.edu/~adityagp/)

Paper is coming soon (with full author list).

[Paper]() \| [Project](https://github.com/ucbepic/DataAgentBench)

</div>
</div>
</div>


<div class="pub-item" data-categories="benchmark">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/capnav.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## CapNav: Benchmarking Vision Language Models on Capability-conditioned Indoor Navigation

[Xia Su](https://xiasu.github.io/)<sup>*</sup>, **Ruiqi Chen**<sup>*</sup>, [Benlin Liu](https://liubl1217.github.io/), [Jingwei Ma](https://jingweim.github.io/), [Zonglin Di](https://scholar.google.com/citations?user=5lFDxsMAAAAJ&hl=en), [Ranjay Krishna](https://ranjaykrishna.com/index.html), [Jon E. Froehlich](https://jonfroehlich.github.io/)

*IEEE/CVF Conference on Computer Vision and Pattern Recognition 2026* (**CVPR2026**)

[Paper](https://arxiv.org/pdf/2602.18424) \| [Project](https://github.com/makeabilitylab/CapNav) \| [Hugging Face](https://huggingface.co/datasets/RichardC0216/CapNav)

</div>
</div>
</div>

<div class="pub-item" data-categories="human-ai">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIDR 2026</div><img src='images/AIOverlord.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Supporting Our AI Overlords: Redesigning Data Systems to be Agent-First

[Shu Liu](https://scholar.google.com/citations?hl=en&user=DB50KvcAAAAJ&view_op=list_works&sortby=pubdate), [Soujanya Ponnapalli](https://soujanyaponnapalli.github.io/), [Shreya Shankar](https://www.sh-reya.com/), [Sepanta Zeighami](https://szeighami.github.io/), [Alan Zhu](https://az1326.github.io/), [Shubham Agarwal](https://skejriwal44.github.io/), **Ruiqi Chen**, [Samion Suwito](https://samion.org/), [Shuo Yuan](https://www.linkedin.com/in/shuo-yuan-395a7b281/), [Ion Stoica](https://people.eecs.berkeley.edu/~istoica/), [Matei Zaharia](https://people.eecs.berkeley.edu/~matei/), [Alvin Cheung](https://people.eecs.berkeley.edu/~akcheung/), [Natacha Crooks](https://nacrooks.github.io/), [Joseph E. Gonzalez](https://people.eecs.berkeley.edu/~jegonzal/), [Aditya G. Parameswaran](https://people.eecs.berkeley.edu/~adityagp/)

*The Conference on Innovative Data Systems Research* (**CIDR2026**)

[Paper](https://arxiv.org/abs/2509.00997)

</div>
</div>
</div>

<div class="pub-item" data-categories="human-ai">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UIST 2025</div><img src='images/FlyMeThrough.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## FlyMeThrough: Human-AI Collaborative 3D Indoor Mapping with Commodity Drones

<a href="https://xiasu.github.io/">Xia Su</a><sup>*</sup>,
<strong>Ruiqi Chen</strong><sup>*</sup>,
<a href="https://jingweim.github.io/">Jingwei Ma</a>,
<a href="https://www.chu-li.me/">Chu Li</a>,
<a href="https://jonfroehlich.github.io/">Jon E. Froehlich</a>

*ACM Symposium on User Interface Software and Technology* (**UIST2025**)

[Paper (PDF)](papers/flymethrough.pdf) \| [Project](https://github.com/makeabilitylab/FlyMeThrough) \| [Website](https://makeabilitylab.cs.washington.edu/project/flymethrough/)

</div>
</div>
</div>

<div class="pub-item" data-categories="benchmark">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UIST 2025</div><img src='images/slideaudit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## SlideAudit: A Dataset and Taxonomy for Automated Evaluation of Presentation Slides

<a href="https://zhuohaozhang.com/">Zhuohao Zhang</a>,
**Ruiqi Chen**,
<a href="https://jszh.github.io/">Mingyuan Zhong</a>,
<a href="https://faculty.washington.edu/wobbrock/">Jacob O. Wobbrock</a>

*ACM Symposium on User Interface Software and Technology* (**UIST2025**)

[Paper (PDF)](papers/slideaudit.pdf) \| [Project](https://github.com/Ruiqi-Chen-0216/SlideAudit)

</div>
</div>
</div>


<div class="pub-item" data-categories="hci">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2025</div><img src='images/NSZT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Immersive Biography: Supporting Intercultural Empathy and Understanding for Displaced Cultural Objects in Virtual Reality

[Ke Zhao](https://scholar.google.com/citations?user=j5KqV84AAAAJ&hl=en), **Ruiqi Chen**, Xiaziyu Zhang, Chenxi Wang, Siling Chen, [Xiaoguang Wang](https://sim.whu.edu.cn/info/1206/6151.htm), [Yujue Wang](https://sim.whu.edu.cn/info/1205/6163.htm), [Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en)

*ACM CHI Conference on Human Factors in Computing Systems* (**CHI2025**)

[Paper (PDF)](papers/ImmersiveBiography.pdf) \| [Project](https://github.com/Ruiqi-Chen-0216/ImmersiveBiography)

</div>
</div>
</div>


<div class="pub-item" data-categories="hci">
<div class="pub-list-paper" markdown="1">

### GestoBrush: Facilitating Graffiti Artists' Digital Creation Experiences through Embodied AR Interactions

**Ruiqi Chen**, [Qingyang He](https://qingyanghe.com/), Hanxi Bao, [Jung E. Choi](https://orcid.org/0000-0003-0058-8281), [Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en)

*ACM International Symposium on Visual Information Communication and Interaction* (**VINCI2025**) \| [Paper (PDF)](papers/GestoBrush.pdf)

🏆<span style="color:red; font-weight:bold;">Best Paper Award</span>

</div>
</div>

<div class="pub-item" data-categories="hci">
<div class="pub-list-paper" markdown="1">

### Parental Perceptions of Children's d/Deaf Identity Shaping Technology Use: A Qualitative Study on Communication Technologies in Mixed-hearing Families

[Keyi Zeng](https://arkxlab.github.io/profile/keyi.html#), Jingyang Lin, **Ruiqi Chen**, [RAY LC](https://raylc.org/), [Pan Hui](https://panhui.people.ust.hk/index.html), [Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en)

*ACM CHI Conference on Human Factors in Computing Systems* (**CHI2025**) [[Paper]](https://doi.org/10.1145/3706599.3719753)

</div>
</div>

<div class="pub-item" data-categories="human-ai">
<div class="pub-list-paper" markdown="1">

### DIAM: Drone-based Indoor Accessibility Mapping

[Xia Su](https://xiasu.github.io/), **Ruiqi Chen**, [Weiye Zhang](https://makeabilitylab.cs.washington.edu/member/richardweiyezhang/), [Jingwei Ma](https://jingweim.github.io/), [Jon E. Froehlich](https://jonfroehlich.github.io/)

*ACM Symposium on User Interface Software and Technology* (**UIST2024**) [[Paper]](https://dl.acm.org/doi/10.1145/3672539.3686782) \| [[Website]](https://makeabilitylab.cs.washington.edu/project/diam/)

</div>
</div>

<div class="pub-item" data-categories="hci">
<div class="pub-list-paper" markdown="1">

### Design and Evaluation of a VR Therapy for Patients with Mild Cognitive Impairment and Dementia: Perspectives from Patients and Stakeholders

**Ruiqi Chen**, Shuhe Wang, [Xuhai Xu](https://orsonxu.com/), Lan Wei, [Yuling Sun](https://www.yulingsun.net/), [Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en)

*IEEE Conference on Virtual Reality and 3D User Interfaces* (**IEEEVR2023**) [[Paper]](https://ieeexplore.ieee.org/document/10108617/)

</div>
</div>

<div class="pub-item" data-categories="human-ai">
<div class="pub-list-paper" markdown="1">

### Exploring Designers' Perceptions and Practices of Collaborating with Generative AI as a Co-creative Agent in a Multi-stakeholder Design Process: Take the Domain of Avatar Design as an Example

[Qingyang He](https://qingyanghe.com/)<sup>\*</sup>, [Weicheng Zheng](https://orcid.org/0009-0002-2550-8823)<sup>\*</sup>, Hanxi Bao, **Ruiqi Chen**, [Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en)

*International Symposium of Chinese Computer-Human Interaction* (**ChineseCHI2023**) [[Paper]](https://dl.acm.org/doi/fullHtml/10.1145/3629606.3629675) \| [[Project]](https://github.com/Ruiqi-Chen-0216/0-Sketch-Paint)

</div>
</div>

<script>
document.querySelectorAll('.filter-btn').forEach(function(btn) {
  btn.addEventListener('click', function() {
    document.querySelectorAll('.filter-btn').forEach(function(b) {
      b.classList.remove('active');
    });
    btn.classList.add('active');
    var filter = btn.getAttribute('data-filter');
    document.querySelectorAll('.pub-item').forEach(function(item) {
      var cats = item.getAttribute('data-categories') || '';
      if (filter === 'all' || cats.split(' ').indexOf(filter) !== -1) {
        item.style.display = '';
      } else {
        item.style.display = 'none';
      }
    });
  });
});
</script>

**About Manuscripts**:

There are several projects currently ongoing:
1. DesignBench: A Benchmark and Annotation System for Design DNA Extraction and Slide Design Evaluation. (advised by Prof. Jacob O. Wobbrock)
2. CapNav-Tune: Fine-Tuning Vision-Language Models for Capability-Aware Indoor Navigation (advised by Prof. Jon E. Froehlich)