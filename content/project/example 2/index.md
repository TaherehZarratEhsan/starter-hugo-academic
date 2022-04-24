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

My master thesis was violence recognition in video sequences. I proposed 5 methods for violece recognition that were published or submitted in international conference and journal magazines. In my first paper, I proposed a handcrafted feature based on human trajectory to differentiate between normal and violence actions. The feature was trained with SVM in supervised mode. In the second method, I trained an CNN with another motion-based feature to categorize action to normal and violene. This method was also supervised. After that, I meticulously analyzed the generalization ability of the state-of-the-art approaches in violece recognition. I found out that the trained model cannot generalize to new unseen enviroment because the existing violence dataset was low-scale. I learned about unsupervised deep learning methods to solve the mentioned problems. In my third paper, I used unsupervised encoder-decoder to learn normal data distribution and any outliers was detected as violence. This method provides higher generality compared to my previous papers. I continued my research in unsupervised representation learning and the results were submitted in two journals. 