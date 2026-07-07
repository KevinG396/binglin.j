---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Washington University in St. Louis</a>. 

profile:
  align: right
  image: jbl.jpg
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
    max-width: 75%;
  }
</style>

I'm Binglin (Kevin) Ji, a recent master's student in Electrical Engineering and Computer Engineering from [Washington University in St. Louis](https://washu.edu). I work on probabilistic AI, particularly principled and efficient probabilistic inference methods in high-dimensional space. I was advised by [Roger Chamberlain](https://www.ccrc.wustl.edu/~roger/) on AI inference and collaborated with [Yevgeniy Vorobeychik](https://engineering.washu.edu/faculty/Yevgeniy-Vorobeychik.html) on generative AI and sampling. Before coming to WashU, I worked at National Laboratory of Pattern Recognition, [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn) and [Lenovo Research](https://research.lenovo.com/webapp/view_English/index.html).

### Research

My goal is to design **probabilistic AI models** and **sampling algorithms** that efficiently address high-dimensional inference while remaining mathematically and computationally tractable. My research interests lie in:

🌟 **Probabilistic Inference**: Given the high sampling and computational cost of training generative models from scratch, inference-time controlled sampling and posterior inference for probabilistic generative models (Diffusion/Flow/Consistency Models) play a crucial role in solving <span style="color: #2DD4BF;"><b>Measure Transport</b></span> problems. My previous research leverages these techniques for this purpose, including: [Sampling](https://arxiv.org/abs/2607.01144),  [Optimal Control over Drift](https://arxiv.org/abs/2607.01144), [new Tree Search Scheme](http://arxiv.org/abs/2607.02915) and Applied Stochastic Processes.


{% include figure.liquid path="assets/img/impfm_dark.png" width="90%" class="img-fluid" %}


**Generative Modeling**: Probabilistic generative models hold great potential for better modeling and solving active discovery/sequential decision-making problems in many scientific and engineering fields. My previous research leverages these models for this purpose, including: [Diffusion Models for active discovery/sequential decision making](https://proceedings.neurips.cc/paper_files/paper/2025/hash/ea8620683340facbd5f754dd169e0980-Abstract-Conference.html) and [Expectation-Maximization via Doob's $h$-transform for white-box decision making](https://proceedings.neurips.cc/paper_files/paper/2025/hash/5d5f4a2f5821c957ff9e4ff14ff37bb9-Abstract-Conference.html).

**Parallel AI Inference**: For complex, high-dimensional data representations (e.g., graph structures), computation itself poses a serious challenge. My previous research addresses this through parallel computing, including: parallelizing Matrix Computation and [Graph Processing](https://ieeexplore.ieee.org/document/11105982).

I am always excited to collaborate, including but not limited to areas such as **AI for Science**, **Scientific Computing** and **Variational Inference**.
