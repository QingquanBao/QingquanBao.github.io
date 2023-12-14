---
title: Visual Model Search and Optimization for Software and Hardware Co-design
summary: Contribute to an open-source graph matching model library!
tags:
  - Deep Learning
  - Computer vision
  - Edge Device
  - Neural Architecture Search
date: '2023-06-09T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Adversarial Attack on Vision Graph Matching
  focal_point: Smart

links: ''
url_code: ''
url_pdf: 'static/uploads/Thesis-Qingquan.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This paper presents a software-hardware co-design framework for efficient neural architecture search and optimization, aiming to address the challenge of traditional neural network architecture design that struggles to meet the demands of various devices and application scenarios. To overcome the limitations of conventional neural architecture search methods that neglect hardware platform constraints and prior knowledge, we propose an automated neural architecture search (NAS) approach that incorporates weight sharing techniques and NSGA-II genetic algorithm to quickly and accurately identify efficient neural architectures that are suitable for specific hardware.

Specifically, we adopt a method that samples sub-networks on a one-shot pre-trained supernet for multi-objective optimization, utilizing weight sharing techniques to accelerate the search process while decoupling model accuracy and hardware performance until the multi-objective search stage. We apply the NSGA-II genetic algorithm to achieve Pareto optimal search and find efficient neural architectures that are compatible with specific hardware platforms.

The contribution of this paper lies in the proposal of a hardware-agnostic, highly extensible, multi-objective output approach that enables users to select models according to their needs while serving as an analysis tool for search space under specific hardware. We evaluate the proposed approach on multiple hardware platforms, including EdgeGPU, Eyeriss, and FPGA, and conduct experiments on a China-domestically-produced AI acceleration chip RockChip RK3588S, demonstrating how this approach can continuously improve the search space to obtain the optimal model under software and hardware constraints. Experimental results indicate that the proposed approach achieves high accuracy and efficient inference performance while demonstrating good generalization performance across different hardware platforms, providing references and insights for research and application in other fields.
