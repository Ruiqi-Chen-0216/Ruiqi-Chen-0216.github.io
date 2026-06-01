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

I am Ruiqi Chen, an incoming Ph.D. student in [Computer Science and Engineering](https://cse.engin.umich.edu/) at the **University of Michigan**. Previously, I was at the **University of Washington**, where I worked with [Prof. Jon E. Froehlich](https://jonfroehlich.github.io/) in [Makeability Lab](https://makeabilitylab.cs.washington.edu/) and [Prof. Jacob O. Wobbrock](https://faculty.washington.edu/wobbrock/) in [ACE Lab](https://depts.washington.edu/acelab/index.html). I also collaborate closely with [Prof. Aditya Parameswaran](https://people.eecs.berkeley.edu/~adityagp/) at the **University of California, Berkeley**.

My research focuses on building and evaluating AI models and systems that align with human knowledge, goals, and values. More broadly, I am interested in how AI systems can better understand what people know, need, and care about, from agentic data systems and multimodal benchmarks to embodied and human-AI applications.

# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Our paper ***CapNav*** has been accepted to CVPR 2026! Proud to be co-first author on my first CVPR paper.
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
  <button class="filter-btn" data-filter="agent">AI Agents</button>
  <button class="filter-btn" data-filter="embodied-ai">Embodied AI</button>
  <button class="filter-btn" data-filter="human-ai">Human-AI</button>
</div>

<div class="pub-item" data-categories="benchmark">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/ArXiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Every Act Has Its Price: Compressed Moral Composition in Frontier LLMs

[Weijia Zhang](https://charliedreemur.github.io/)<sup>*</sup>,
**Ruiqi Chen**<sup>*</sup>,
[Yunze Xiao](https://algoroxyolo.github.io/)<sup>*</sup>,
[Weihao Xuan](https://weihaoxuan.com/)

*Preprint*

Paper coming soon.

</div>
</div>
</div>


<div class="pub-item" data-categories="benchmark">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/BeyondAgreement.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Beyond Agreement: Scoring Panel-Surfaced Biomedical Entity Candidates for Curator Triage

Shuheng Cao<sup>*</sup>,
**Ruiqi Chen**<sup>*</sup>,
[Renjie Cao](https://scholar.google.com/citations?user=H6wYLmwAAAAJ&hl=en),
[Zhenhao Zhang](https://zhangzhh.cn/),
[Siyu Zhang](https://scholar.google.com/citations?user=T_XVf3EAAAAJ&hl=en&oi=sra),
[Tingting Dan](https://scholar.google.com/citations?user=FMcmg0gAAAAJ&hl=en&oi=ao)

*Preprint*

[Paper](http://arxiv.org/abs/2605.30826)

</div>
</div>
</div>


<div class="pub-item" data-categories="embodied-ai human-ai agent">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/ArXiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Holistic Human Intent-Conditioned Planning for Autonomous Driving

[Xuewen Luo](https://scholar.google.com/citations?user=QzVrwt4AAAAJ&hl=en),
Ding Fan,
**Ruiqi Chen**,
Ye Cao,
Xiujin Liu,
Bo Yu,
Fengze Yang,
[Chenxi Liu](https://chenxiliu-dylan.github.io/)

*Preprint*

Paper coming soon.

</div>
</div>
</div>


<div class="pub-item" data-categories="benchmark">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/ArXiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## How Much Vision Does Multimodal Reasoning Need? Vision-Stripping for Multimodal Benchmarks

[Weijia Zhang](https://charliedreemur.github.io/),
[Zijia Liu](https://scholar.google.com/citations?hl=zh-CN&user=17f5_L4AAAAJ),
[Tianyi Zhang](https://pinkstrokes.com/),
**Ruiqi Chen**,
Lian Zhang,
Haoru Li,
Haoqi Chen,
[Jiaxuan You](https://cs.stanford.edu/~jiaxuan/)

*Preprint*

Paper coming soon.

</div>
</div>
</div>


<div class="pub-item" data-categories="embodied-ai agent">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/ArXiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Event-Aware Action Routing for Illumination-Robust Vision-Language-Action Policies

Jiaxin Liu,
Xun Xu,
[Zhenhao Zhang](https://zhangzhh.cn/),
Hanqing Wang,
**Ruiqi Chen**,
Shi Chang,
Weiyu Guo,
Laurent Kneip

*Preprint*

Paper coming soon.

</div>
</div>
</div>


<div class="pub-item" data-categories="benchmark agent">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/DAB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Can AI Agents Answer Your Data Questions? A Benchmark for Data Agents

[Ruiying Ma](https://ruiying-ma.github.io/)<sup>*</sup>,
[Shreya Shankar](https://www.sh-reya.com/)<sup>*</sup>, 
**Ruiqi Chen**,
[Yiming Lin](https://yiminglin18.com/),
[Sepanta Zeighami](https://szeighami.github.io/),
Rajoshi Ghosh, Abhinav Gupta, Anushrut Gupta, Tanmai Gopal,
[Aditya G. Parameswaran](https://people.eecs.berkeley.edu/~adityagp/)

*Preprint*

[Paper](https://arxiv.org/abs/2603.20576v1) \| [Github](https://github.com/ucbepic/DataAgentBench) \| [Website](https://ucbepic.github.io/DataAgentBench/)

</div>
</div>
</div>


<div class="pub-item" data-categories="benchmark embodied-ai">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/capnav.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## CapNav: Benchmarking Vision Language Models on Capability-conditioned Indoor Navigation

[Xia Su](https://xiasu.github.io/)<sup>*</sup>, **Ruiqi Chen**<sup>*</sup>, [Benlin Liu](https://liubl1217.github.io/), [Jingwei Ma](https://jingweim.github.io/), [Zonglin Di](https://scholar.google.com/citations?user=5lFDxsMAAAAJ&hl=en), [Ranjay Krishna](https://ranjaykrishna.com/index.html), [Jon E. Froehlich](https://jonfroehlich.github.io/)

*IEEE/CVF Conference on Computer Vision and Pattern Recognition 2026* (**CVPR2026**)

[Paper](https://arxiv.org/pdf/2602.18424) \| [Github](https://github.com/makeabilitylab/CapNav) \| [Hugging Face](https://huggingface.co/datasets/RichardC0216/CapNav) \| [Website](https://makeabilitylab.github.io/CapNav/)

</div>
</div>
</div>

<div class="pub-item" data-categories="agent">
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

[Paper (PDF)](papers/flymethrough.pdf) \| [Github](https://github.com/makeabilitylab/FlyMeThrough) \| [Website](https://makeabilitylab.cs.washington.edu/project/flymethrough/)

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

[Paper (PDF)](papers/slideaudit.pdf) \| [Github](https://github.com/Ruiqi-Chen-0216/SlideAudit)

</div>
</div>
</div>


<div class="pub-item" data-categories="">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2025</div><img src='images/NSZT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Immersive Biography: Supporting Intercultural Empathy and Understanding for Displaced Cultural Objects in Virtual Reality

[Ke Zhao](https://scholar.google.com/citations?user=j5KqV84AAAAJ&hl=en), **Ruiqi Chen**, Xiaziyu Zhang, Chenxi Wang, Siling Chen, [Xiaoguang Wang](https://sim.whu.edu.cn/info/1206/6151.htm), [Yujue Wang](https://sim.whu.edu.cn/info/1205/6163.htm), [Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en)

*ACM CHI Conference on Human Factors in Computing Systems* (**CHI2025**)

[Paper (PDF)](papers/ImmersiveBiography.pdf) \| [Github](https://github.com/Ruiqi-Chen-0216/ImmersiveBiography)

</div>
</div>
</div>


<div class="pub-item" data-categories="">
<div class="pub-list-paper" markdown="1">

### GestoBrush: Facilitating Graffiti Artists' Digital Creation Experiences through Embodied AR Interactions

**Ruiqi Chen**, [Qingyang He](https://qingyanghe.com/), Hanxi Bao, [Jung E. Choi](https://orcid.org/0000-0003-0058-8281), [Xin Tong](https://scholar.google.ca/citations?user=XIM08ZwAAAAJ&hl=en)

*ACM International Symposium on Visual Information Communication and Interaction* (**VINCI2025**) [Paper (PDF)](papers/GestoBrush.pdf)

🏆<span style="color:red; font-weight:bold;">Best Paper Award</span>

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
