---
title: Modular Gait Optimization - From Unit Moves to Full Trajectory in Bipedal Systems
summary: Let's see how to train your baby Biped w/o learning!
tags:
  - Robotics
  - Trajecotry Optimization
date: '2023-12-09T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links: ""
url_code: 'https://github.com/QingquanBao/2DBiped'
url_pdf: 'https://github.com/QingquanBao/2DBiped/blob/main/MEAM517_final_report.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Our project is aimed at trajectory optimization in bipedal robotics, specifically in three fundamental gaits: hopping, walking, and running. The central challenge we address is the computational complexity often encountered in multi-step trajectory optimizations. Typically, these optimizations yield gaits that do not align with natural human movements, a gap that our work aims to bridge.

We've developed the Gait Modularization Optimization Technique (GMOT) to generate more natural gait trajectories efficiently. GMOT stands out for its unique two-loop approach. In the inner loop, we focus on designing and optimizing a repeatable gait unit, applying symmetry constraints to the initial and final states for consistency and efficiency. In the outer loop, these optimized gait units serve as a foundation for optimizing the full gait trajectory.

Our method, GMOT, has demonstrated remarkable results. It not only aligns more closely with human-like movement patterns but also significantly reduces the time required for solving complex trajectory optimization problems compared to traditional methods with naive initialization. In essence, GMOT is set to transform the way we approach bipedal robotic movement, making it more efficient, stable, and, importantly, more akin to natural human motion.
