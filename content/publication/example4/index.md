---
title: "Learning Deep Latent Space for Unsupervised Violence Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Manoochehr Nahvi
- Seyed Mehdi Mohtavipour


date: "2023-03-23"
doi: "https://doi.org/10.1007/s11042-022-13827-7"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-23"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In Multimedia tools and application journal
publication_short: In Multimedia tools and application journal

abstract: Numerous violent actions occur in the world every day, affecting victims mentally and physically. To reduce violence rates in society, an automatic system may be required to analyze human activities quickly and detect violent actions accurately. Violence detection is a complex machine vision problem involving insufficient violent datasets and wide variation in activities and environments. In this paper, an unsupervised framework is presented to discriminate between normal and violent actions overcoming these challenges. This is accomplished by analyzing the latent space of a double-stream convolutional AutoEncoder (AE). In the proposed framework, the input samples are processed to extract discriminative spatial and temporal information. A human detection approach is applied in the spatial stream to remove background environment and other noisy information from video segments. Since motion patterns in violent actions are entirely different from normal actions, movement information is processed with a novel Jerk feature in the temporal stream. This feature describes the long-term motion acceleration and is composed of 7 consecutive frames. Moreover, the classification stage is carried out with a one-class classifier using the latent space of AEs to identify the outliers as violent samples. Extensive experiments on Hockey and Movies datasets showed that the proposed framework surpassed the previous works in terms of accuracy and generality.

# Summary. An optional shortened abstract.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://rad-bunny-95c815.netlify.app/publication/example3/example3.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---
