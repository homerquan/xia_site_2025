---
title: "Augmenting Indoor Inertial Tracking with Polarized Light"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhao Tian 
- Yu-Lin Wei 
- Wei-Nin Chang 
- Xi Xiong 
- Changxi Zheng 
- Hsin-Mu Tsai 
- Kate Ching-Ju Lin 
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ACM International Conference on Mobile Systems, Applications, and Services (MobiSys), 2018.
publication_short: MobiSys
award: ""

abstract: "Inertial measurement unit (IMU) has long suffered from the problem of integration drift, where sensor noises accumulate quickly and cause fast-growing tracking errors. Existing methods for calibrating IMU tracking either require human in the loop, or need energy-consuming cameras, or suffer from coarse tracking granularity. We propose to augment indoor inertial tracking by reusing existing indoor luminaries to project a static light polarization pattern in the space. This pattern is imperceptible to human eyes and yet through a polarizer, it becomes detectable by a color sensor, and thus can serve as fine-grained optical landmarks that constrain and correct IMU's integration drift and boost tracking accuracy. Exploiting the birefringence optical property of transparent tapes -- a low-cost and easily-accessible material -- we realize the polarization pattern by simply adding to existing light cover a thin polarizer film with transparent tape stripes glued atop. When fusing with IMU sensor signals, the light pattern enables robust, accurate and low-power motion tracking. Meanwhile, our approach entails low deployment overhead by reusing existing lighting infrastructure without needing an active modulation unit. We build a prototype of our light cover and the sensing unit using off-the-shelf components. Experiments show 4.3 cm median error for 2D tracking and 10 cm for 3D tracking, as well as its robustness in diverse settings."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# do not open its dedicated page
nopage: true

# Custom links (uncomment lines below)
links:
- name: Video
  url: https://www.youtube.com/watch?v=i2AS7rWZC7M

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
