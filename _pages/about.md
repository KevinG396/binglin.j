---
layout: about
title: about
permalink: / 
subtitle: <a href='#'>Building efficient Probabilistic AI.</a>

profile:
  align: right
  image: ji.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>binglin.j@wustl.edu</p>
    <p>STL, MO 63105</p>

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder
  
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

---

<style>
  .profile img {
    max-width: 85%;
  }
  .sdm-block::after {
    content: "";
    display: block;
    clear: both;
  }
  .sdm-video {
    float: left;
    width: 32%;
    aspect-ratio: 1 / 1;
    margin: 0.35rem 0.75rem 0.5rem 0;
    border-radius: 0.25rem;
  }
  
  @media (min-width: 576px) {
    .sdm-block {
      display: flex;
      align-items: center;
      gap: 1.5rem;
      margin-bottom: 1rem;
    }
    .sdm-block::after {
      content: none;
    }
    .sdm-video {
      float: none;
      flex: 0 0 13%;
      width: 13%;
      margin: 0;
    }
    .sdm-block p {
      margin-bottom: 0;
    }
  }
</style>

I'm Binglin (Kevin) Ji, a recent master's student in Electrical Engineering and Computer Engineering from [Washington University in St. Louis](https://washu.edu). I work on probabilistic AI, particularly principled and efficient probabilistic inference methods in high-dimensional space. I was advised by [Roger Chamberlain](https://www.ccrc.wustl.edu/~roger/) on AI inference and collaborated with [Yevgeniy Vorobeychik](https://engineering.washu.edu/faculty/Yevgeniy-Vorobeychik.html) on generative AI and sampling. Before coming to WashU, I worked at National Laboratory of Pattern Recognition, [Institute of Automation, Chinese Academy of Sciences (Beijing)](http://english.ia.cas.cn) and [Lenovo Research](https://research.lenovo.com/webapp/view_English/index.html).

### Research Interests

I'm working on `generative models` and `sampling algorithms` that are mathematically principled yet computationally efficient in high-dimensional spaces. I'm always excited to collaborate on topics such as **AI4Science**, **Scientific Computing**, **Optimal Transport** and **Variational Inference**. More specifically, my interests lie in:

<div class="sdm-block">
  <video src="{{ '/assets/video/transport.mp4' | relative_url }}"
         class="sdm-video"
         autoplay muted loop playsinline preload="metadata"></video>
  <p>🌟 <b>Probabilistic Inference</b> <br>Probabilistic inference provides the main machinery for dynamical measure transport, the question of how one probability measure is driven into another along a continuous-time trajectory. My work develops sampling and variational inference methods over high-dimensional SDEs/ODEs, making transport efficient and controllable in Diffusion/Flow/Consistency models: <a href="https://arxiv.org/abs/2607.01144"><span style="color: #FF8C00;">Sequential Monte Carlo</span></a>, <a href="https://arxiv.org/abs/2607.01144"><span style="color: #A582C8;">Interacting Particle Drift Correction</span></a>, <a href="https://arxiv.org/abs/2607.02915">Tree Search Scheme</a>, and <a href="https://arxiv.org/abs/2609.06761"><span style="color: #86C98F;">Applied Stochastic Processes</span></a>.</p>
</div>

{% comment %}
{% include figure.liquid path="assets/img/impfm_dark.png" width="93%" class="img-fluid d-block mx-auto" %}
{% endcomment %}

<div class="sdm-block">
  <video src="{{ '/assets/video/sdm.mp4' | relative_url }}"
         class="sdm-video"
         autoplay muted loop playsinline preload="metadata"></video>
    <p><b>Generative Modeling for Decision Making</b> <br>Generative models offer a tractable way to represent <b>uncertainty</b> in high-dimensional spaces, and thereby hold great potential for sequential decision-making problems. My previous research leverages these models for this purpose, including: Diffusion Models for <a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/ea8620683340facbd5f754dd169e0980-Abstract-Conference.html">Active Discovery/Sequential Decision Making</a> and <a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/5d5f4a2f5821c957ff9e4ff14ff37bb9-Abstract-Conference.html"><span style="color: #FF8C00;">Expectation-Maximization via Doob&rsquo;s \(h\)-transform</span></a> for white-box decision making.</p>
</div>


<div class="sdm-block">
  <video src="{{ '/assets/video/graph.mp4' | relative_url }}"
         class="sdm-video"
         autoplay muted loop playsinline preload="metadata"></video>
  <p><b>Parallel AI Inference</b> <br>For complex, high-dimensional data representations (e.g., graph-structured data), computation itself poses serious challenges in terms of performance and scalability. My previous research addresses this through high-performance/parallel computing techniques, including: <a href="https://ieeexplore.ieee.org/document/11105982"><span style="color: #86C98F;">Graph Processing</span></a> and parallelizing Matrix Computation.</p>
</div>
