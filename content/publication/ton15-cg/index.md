---
title: "Practical Conflict Graphs in the Wild"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zengbin Zhang 
- Gang Wang 
- Xiaoxiao Yu 
- Ben Y. Zhao 
- Haitao Zheng

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2014-03-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Networking (ToN), 2014"
publication_short: "ToN"
award: ""

abstract: "Today, most spectrum allocation algorithms use conflict graphs to capture interference conditions. The use of conflict graphs, however, is often questioned by the wireless community for two reasons. First, building accurate conflict graphs requires significant overhead, and hence does not scale to outdoor networks. Second, conflict graphs cannot properly capture accumulative interference. In this paper, we use large-scale measurement data as ground truth to understand how severe these problems are and whether they can be overcome. We build “practical” conflict graphs using measurement-calibrated propagation models, which remove the need for exhaustive signal measurements by interpolating signal strengths using calibrated models. Calibrated models are imperfect, and we study the impact of their errors on multiple steps in the process, from calibrating propagation models, predicting signal strengths, to building conflict graphs. At each step, we analyze the introduction, propagation, and final impact of errors by comparing each intermediate result to its ground-truth counterpart. Our work produces several findings. Calibrated propagation models generate location-dependent prediction errors, ultimately producing conservative conflict graphs. While these “estimated conflict graphs” lower spectrum utilization, their conservative nature improves reliability by reducing the impact of accumulative interference. Finally, we propose a graph augmentation technique to address remaining accumulative interference."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# do not open its dedicated page
nopage: true

# Custom links (uncomment lines below)
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: false

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: false
---