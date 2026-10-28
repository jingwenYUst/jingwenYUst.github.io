---
layout: single
title: "Enhancing Glass Surface Reconstruction via Depth Prior for Robot Navigation"
permalink: /papers/glassrecon/
author_profile: true
seo_title: "Enhancing Glass Surface Reconstruction via Depth Prior for Robot Navigation"
description: "Jiamin Zheng, Jingwen Yu, Guangcheng Chen, Hong Zhang. IROS 2026. Best Paper Finalist (10/1,933)."
scholar_meta: true
citation_title: "Enhancing Glass Surface Reconstruction via Depth Prior for Robot Navigation"
citation_authors:
  - "Jiamin Zheng"
  - "Jingwen Yu"
  - "Guangcheng Chen"
  - "Hong Zhang"
citation_publication_date: "2026"
citation_pdf_path: "/papers/glassrecon/glassrecon-v3.pdf"
---

<p>
  <strong>Jiamin Zheng</strong><sup>*</sup>, <strong>Jingwen Yu</strong><sup>*</sup>, Guangcheng Chen, Hong Zhang
  <br>
  <sup>*</sup> Equal contribution.
</p>

<p>
  <em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026.</em><br>
  <strong>Best Paper Finalist: 10/1,933 (Top 0.52%).</strong>
</p>

<p>
  <a href="/papers/glassrecon/glassrecon-v3.pdf"><img alt="PDF" src="https://img.shields.io/badge/PDF-Download-brightgreen.svg"/></a>
  <a href="https://arxiv.org/abs/2604.18336"><img alt="arXiv" src="https://img.shields.io/badge/ArXiv-2604.18336-004088.svg"/></a>
  <a href="https://jarvisyjw.github.io/GlassRecon/"><img alt="Project Page" src="https://img.shields.io/badge/Project-Page-blue?style=flat"/></a>
  <a href="https://github.com/JMamie/GlassRecon"><img alt="Code" src="https://img.shields.io/github/stars/JMamie/GlassRecon"/></a>
</p>

## Abstract

Indoor robot navigation is often compromised by glass surfaces, which severely corrupt depth sensor measurements. While foundation models like Depth Anything 3 provide excellent geometric priors, they lack an absolute metric scale. We propose a training-free framework that leverages depth foundation models as a structural prior, employing a robust local RANSAC-based alignment to fuse it with raw sensor depth. This naturally avoids contamination from erroneous glass measurements and recovers an accurate metric scale. Furthermore, we introduce GlassRecon, a novel RGB-D dataset with geometrically derived ground truth for glass regions. Extensive experiments demonstrate that our approach consistently outperforms state-of-the-art baselines, especially under severe sensor depth corruption. The dataset and related code are available at <https://github.com/JMamie/GlassRecon>.

## Links

- Full text (PDF, v3): <a href="/papers/glassrecon/glassrecon-v3.pdf">glassrecon-v3.pdf</a>
- arXiv: <https://arxiv.org/abs/2604.18336>
- Project page: <https://jarvisyjw.github.io/GlassRecon/>
- Code and dataset: <https://github.com/JMamie/GlassRecon>