---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Washington University in St. Louis</a>. 

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

I'm Binglin (Kevin) Ji, a recent master's student in Electrical Engineering and Computer Engineering from [Washington University in St. Louis](https://washu.edu). I work on probabilistic AI, particularly principled and efficient probabilistic inference methods in high-dimensional space. I was advised by [Roger Chamberlain](https://www.ccrc.wustl.edu/~roger/) on AI inference and collaborated with [Yevgeniy Vorobeychik](https://engineering.washu.edu/faculty/Yevgeniy-Vorobeychik.html) on generative AI and sampling. Before coming to WashU, I worked at National Laboratory of Pattern Recognition, [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn) and [Lenovo Research](https://research.lenovo.com/webapp/view_English/index.html).

### Research Interests

My goal is to design probabilistic models and sampling algorithms that are mathematically principled yet computationally efficient for high-dimensional inference. I'm always excited to collaborate, including but not limited to areas such as **AI for Science**, **Scientific Computing** and **Variational Inference**. My research interests lie in:

<div class="sdm-block">
  <video src="{{ '/assets/video/transport.mp4' | relative_url }}"
         class="sdm-video"
         autoplay muted loop playsinline preload="metadata"></video>
  <p>🌟 <b>Probabilistic Inference</b> <br>Sampling and variational inference for high-dimensional SDEs/ODEs provide a principled framework for solving <span style="color: #2DD4BF;"><b>Measure Transport</b></span> problems. My previous research leverages some of these techniques on probabilistic generative models (Diffusion/Flow/Consistency Models), including: <a href="https://arxiv.org/abs/2607.01144"><span style="color: #FF8C00;">Sampling</span></a>, <a href="https://arxiv.org/abs/2607.01144"><span style="color: #A582C8;">Optimal Control over Drift</span></a>, <a href="https://arxiv.org/abs/2607.02915">Tree Search Scheme</a>, and <a href="https://arxiv.org/abs/2609.06761"><span style="color: #86C98F;">Applied Stochastic Processes</span></a>.</p>
</div>


{% include figure.liquid path="assets/img/impfm_dark.png" width="90%" class="img-fluid d-block mx-auto" %}

<div class="sdm-block">
  <video src="{{ '/assets/video/sdm.mp4' | relative_url }}"
         class="sdm-video"
         autoplay muted loop playsinline preload="metadata"></video>
    <p><b>Generative Modeling for Decision Making</b> <br>Probabilistic generative models hold great potential for better modeling and solving sequential decision-making problems in many scientific and engineering fields. My previous research leverages these models for this purpose, including: Diffusion Models for <a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/ea8620683340facbd5f754dd169e0980-Abstract-Conference.html">Active Discovery/Sequential Decision Making</a> and <a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/5d5f4a2f5821c957ff9e4ff14ff37bb9-Abstract-Conference.html"><span style="color: #86C98F;">Expectation-Maximization via Doob&rsquo;s \(h\)-transform</span></a> for white-box decision making.</p>
</div>


<div class="sdm-block">
  <video src="{{ '/assets/video/graph.mp4' | relative_url }}"
         class="sdm-video"
         autoplay muted loop playsinline preload="metadata"></video>
  <p><b>Parallel AI Inference</b> <br>For complex, high-dimensional data representations (e.g., graph structures), computation itself poses serious challenges in terms of performance and scalability. My previous research addresses this through high-performance/parallel computing techniques, including: parallelizing Matrix Computation and <a href="https://ieeexplore.ieee.org/document/11105982">Graph Processing</a>.</p>
</div>
