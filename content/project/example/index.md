---
title: Semantic SLAM towards Outdoor Dynamic Environment  
summary: 
  - Used ORB-SLAM2 as the framework, run the algorithm under Ubuntu 18.04 and verified the effectiveness of the proposed algorithm with KITTI dataset and ZED2 self-collection dataset.
  - Embedded the Deeplabv3+ semantic segmentation model into the stereo model of ORB-SLAM2 to guarantee recognition of dynamic objects.
  -	Determined the dynamic hierarchy of objects in the scene based on the prior knowledge.
  -	Propose a dynamic model to judge the motion status of objects by comparing the pixel displacement.
  -	Designed a feature selection strategy to discard the feature points of dynamic regions.

tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image:
  #caption: Photo by rawpixel on Unsplash
  #focal_point: Smart

#links:
  #- icon: twitter
  #  icon_pack: fab
  #  name: Follow
  #  url: https://twitter.com/georgecushen
#url_code: ''
#url_pdf: ''
#url_slides: ''
#url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
