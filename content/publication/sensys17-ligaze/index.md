---
title: "Ultra-Low Power Gaze Tracking for Virtual Reality"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tianxing Li 
- Qiang Liu 
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2017-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ACM Conference on Embedded Networked Sensor Systems (SenSys), 2017.
publication_short: SenSys
award: "Best Paper Candidate. SIGMOBILE Research Highlight"

abstract: "Tracking user's eye fixation direction is crucial to virtual reality (VR): it eases user's interaction with the virtual scene and enables intelligent rendering to improve user's visual experiences and save system energy. Existing techniques commonly rely on cameras and active infrared emitters, making them too expensive and power-hungry for VR headsets (especially mobile VR headsets).

We present LiGaze, a low-cost, low-power approach to gaze tracking tailored to VR. It relies on a few low-cost photodiodes, eliminating the need for cameras and active infrared emitters. Reusing light emitted from the VR screen, LiGaze leverages photodiodes around a VR lens to measure reflected screen light in different directions. It then infers gaze direction by exploiting pupil's light absorption property. The core of LiGaze is to deal with screen light dynamics and extract changes in reflected light related to pupil movement. LiGaze infers a 3D gaze vector on the fly using a lightweight regression algorithm. We design and fabricate a LiGaze prototype using off-the-shelf photodiodes. Our comparison to a commercial VR eye tracker (FOVE) shows that LiGaze achieves 6.3° and 10.1° mean within-user and cross-user accuracy. Its sensing and computation consume 791μW in total and thus can be completely powered by a credit-card sized solar cell harvesting energy from indoor lighting. LiGaze's simplicity and ultra-low power make it applicable in a wide range of VR headsets to better unleash VR's potential."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# do not open its dedicated page
nopage: true

# Custom links (uncomment lines below)
links:
- name: Project website
  url: http://dartnets.cs.dartmouth.edu/ligaze

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=l_AkoQNGkGw&feature=youtu.be'

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

