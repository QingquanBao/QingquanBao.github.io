---
title: 'Embodied Depth Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yilun Du
  - Feng Chen
  - Leslie Pack Kaelbling
  - Tomás Lozano-Pérez
  - Chuang Gan
  - Joshua B. Tenenbaum

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: '' 
publication_short: ''

abstract: We study the problem of embodied depth prediction, where an embodied agent in an environment must learn to accurately estimate the depth of its surroundings. Such a task can be useful for embodied AI where it is highly desirable to accurately predict 3D structure when deploying robots in novel environments. However, directly using existing pre-trained depth prediction models in this setting is difficult as images are often captured in out-of-distribution viewpoints. Instead, it is important to construct a system that may adapt and learn depth prediction by interacting and gathering information from the environment and which may utilize the rich information in past observations captured from ego-motion. Towards this problem, we propose a framework for actively interacting with the environment to learn depth prediction, leveraging both explorations of new areas of space and exploration of areas of space where depth prediction is inconsistent. To exploit the rich information captured from past observations in the embodied setting, we further jointly utilize current and past image observations and their corresponding egomotions to predict depth. We illustrate the efficacy of our approach in obtaining accurate depth predictions in both simulated and real household environments.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - embodied

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}
