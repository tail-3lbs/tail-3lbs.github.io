---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='page-top'></span>

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><a href='https://machineperceptionlab.github.io/ShorterSplatting-Project/' target="_blank" rel="noopener noreferrer"><img src='images/cvpr26/tease.png' alt='ShorterSplatting teaser' width='100%'></a></div></div>
<div class='paper-box-text' markdown="1">

<span class="paper-title">Speeding Up the Learning of 3D Gaussians with Much Shorter Gaussian Lists</span>

[Jiaqi Liu](/), <a href="https://h312h.github.io/" target="_blank" rel="noopener noreferrer">Zhizhong Han</a>

**CVPR 2026**

<a href="https://arxiv.org/abs/2603.09277" target="_blank" rel="noopener noreferrer">arXiv</a>&nbsp;&nbsp;&nbsp;<a href="https://machineperceptionlab.github.io/ShorterSplatting-Project/" target="_blank" rel="noopener noreferrer">Project</a>&nbsp;&nbsp;&nbsp;<a href="https://github.com/MachinePerceptionLab/ShorterSplatting" target="_blank" rel="noopener noreferrer">Code</a>
</div>
</div>

<div style="height: 2rem;"></div>

<span class='anchor' id='projects'></span>

# Projects

<div class='paper-box'><div class='paper-box-image'><div><a href='https://tail-3lbs.github.io/3DGSSceneExplorer/' target="_blank" rel="noopener noreferrer"><img src='images/3dvision/teaser-room.png' alt='3DGS Scene Explorer teaser' width='100%'></a></div></div>
<div class='paper-box-text' markdown="1">

<span class="paper-title">3DGS Scene Explorer</span>

An interactive landing page for exploring standalone 3D Gaussian Splatting viewers, including multi-view scene layouts and two-view match-ray demos.

<a href="https://tail-3lbs.github.io/3DGSSceneExplorer/" target="_blank" rel="noopener noreferrer">Open Site</a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><a href='https://tail-3lbs.github.io/3DGSEllipseViewer/' target="_blank" rel="noopener noreferrer"><img src='images/3dgs_ellipse/teaser.png' alt='3DGS Ellipse Viewer teaser' width='100%'></a></div></div>
<div class='paper-box-text' markdown="1">

<span class="paper-title">3DGS Ellipse Viewer</span>

A static comparison page for per-view 2D Gaussian ellipse visualizations across 9 Mip-NeRF 360 scenes, contrasting COLMAP initialization with the trained model.

<a href="https://tail-3lbs.github.io/3DGSEllipseViewer/" target="_blank" rel="noopener noreferrer">Open Site</a>
</div>
</div>
