---
title: Violence Recognition in Video Sequences
summary: " "
tags:
- Deep Learning
date: "2022-04-01"

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Throughout my research endeavors, I have developed a robust foundation in computer vision, machine learning, and deep learning. This expertise is reflected in seven published papers focusing on violence detection to date. In the initial stages, I designed handcrafted features based on motion patterns to discriminate between violent and normal actions. As my research progressed, I delved into deep learning techniques such as CNNs and LSTMs.

However, the effectiveness of deep networks relies heavily on extensive datasets to automatically identify patterns and extract features from complex data. Faced with the constraints of a limited annotated dataset, challenges in this domain often arise in generalizing to Out-of-Distribution data. Acknowledging this hurdle, I redirected my efforts toward enhancing generalizability. Leveraging the available large-scale normal action recognition datasets, I pre-trained the model to incorporate valuable knowledge, enabling it to comprehensively learn normal patterns. By framing violence recognition as anomaly action recognition, I successfully detected abnormal human actions. To achieve this, I proposed various techniques, including representation learning using AE and generative modeling through GAN. Notably, prior to my research, there had been no comprehensive investigation into increasing generalization in violence recognition.

In comparison to state-of-the-art methodologies, my contributions have yielded substantial results, showcasing a remarkable 40% improvement in generalization accuracy across new real-world environments. 