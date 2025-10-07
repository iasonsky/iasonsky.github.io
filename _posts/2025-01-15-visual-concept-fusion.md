---
layout: post
title:  "Injecting Image Guidance into Text-Conditioned Diffusion Models at Inference"
date:   2025-01-15 23:59:59 +00:00
image: /images/publications/visual-concept-fusion.png
categories: research
author: "Iason Skylitsis"
authors: Agata Żywot, <strong>Iason Skylitsis</strong>, Thijmen Nijdam, Zoe Tzifa-Kratira, Derck W. E. Prinzhorn, Konrad Szewczyk
# venue: 
note: Ongoing Project
paper: docs/visual-concept-fusion-report.pdf
code: https://github.com/thijmennijdam/stable-diffusion-v2
poster: docs/visual-concept-fusion-poster.pdf
# video: 
# slides: 
# blogpost: 
---

<ul>
  <li>Introduced Visual Concept Fusion (VCF), the first method enabling dual conditioning on both image and text prompts at inference time without retraining</li>
  <li>Developed a lightweight aligner using InfoNCE and cross-attention reconstruction losses to map image tokens to text embedding space</li>
  <li>Implemented a fusion strategy that preserves both textual and visual semantics</li>
  <li>Added optional Prompt-Noise Optimization module for test-time refinement</li>
</ul>
