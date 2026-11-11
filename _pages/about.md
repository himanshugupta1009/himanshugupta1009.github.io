---
layout: about
title: About
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

# News, selected publications and writing are rendered at the end of this file
# (instead of by the layout) so the Writing section can sit below publications.
selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

I am a PhD student in Aerospace Engineering at the University of Colorado Boulder, co-advised by Professors [Zachary Sunberg](https://www.colorado.edu/aerospace/zachary-sunberg) and [Bradley Hayes](https://www.cairo-lab.com/).

My research is about **robot decision making under uncertainty**. Robots that work alongside people, or that collect data in unpredictable environments, rarely know the full state of the world. I build planning algorithms that reason about this uncertainty directly and still run fast enough for real robots. My work covers:

- **Continuous-space POMDPs and BeliefMDPs:** online tree search and belief-space planning methods that scale to continuous states, actions and observations.
- **Autonomous navigation among people:** intention-aware navigation in crowds, and planning to intercept moving targets instead of driving to fixed goals.
- **Active information gathering:** deciding where a robot should go to learn the most, for example sending autonomous vehicles to observe severe weather.
- **Multi-robot motion planning:** scaling coordination to many robots under kinodynamic constraints via precomputed, translation-invariant primitives.
{: style="overflow: hidden;"}

Before my PhD, I earned an M.S. in Computer Science at CU Boulder, where my thesis was on autonomous navigation among dynamic obstacles. Before that, I spent two years as a data engineer and scientist at [JioSaavn](https://www.jiosaavn.com/), building large-scale recommendation systems. I received my B.Tech in Computer Science from [IIT Ropar](https://www.iitrpr.ac.in/). In summer 2023, I was a research intern in Prof. Han-Lim Choi's lab at KAIST, working on multi-robot motion planning.

**I am looking for research internships for Summer 2027** in motion planning, autonomous systems and robot learning. Please feel free to reach out.

<div>
<h2 class="section-heading"><a href="/news/" style="color: inherit">News</a></h2>
{% include news.liquid limit=true %}
</div>

<div>
<h2 class="section-heading"><a href="/publications/" style="color: inherit">Selected publications</a></h2>
{% include selected_papers.liquid %}
</div>

<div>
<h2 class="section-heading">Writing</h2>
<ul>
  <li><a href="https://medium.com/correll-lab/building-clip-from-scratch-to-identify-sports-celebrities-7d0502edae3d">Building CLIP from Scratch to Identify Sports Celebrities</a> · Medium, Dec 2024</li>
  <li><a href="https://medium.com/correll-lab/paper-review-set-transformers-6ce59c2ad88f">Paper Review: Set Transformers</a> · Medium, Dec 2024</li>
</ul>
</div>

<style id="section-heading-style">
h2.section-heading { border-left: 4px solid var(--global-theme-color); padding-left: 0.75rem; line-height: 1.2; margin-top: 2.5rem; margin-bottom: 1.25rem; }
</style>
