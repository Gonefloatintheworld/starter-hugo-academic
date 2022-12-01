---
title: 'Internal Defect Detection of Overhead Aluminum Conductor Composite Core Transmission Lines with an Inspection Robot and Computer Vision'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Fei Wang
  - Guangming Song
  - Juzheng Mao
  - admin

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Instrumentation and Measurement*
publication_short: reject and resubmit in *TIM*

abstract: Overhead aluminum conductor composite core (ACCC) transmission lines are applied extensively. However, internal defects of ACCC wires are difficult to be detected, threatening the stability and security of the grid. Thus, a novel automatic detection system using an inspection robot and an object detection model is proposed to solve the problem of detecting internal defects of ACCC wires. Firstly, a new inspection robot with an non-destructive testing (NDT) system consisting of a digital radiography (DR) detection panel and a portable X-ray generator is developed to acquire the X-ray images of ACCC wires. Then, the IN-ACCC dataset is created by acquiring X-ray images of artificial defective ACCC wires and then processing, classifying, and labeling the images. Finally, an anchor-free object detection model named CenterNet-NDT is proposed based on CenterNet. CenterNet-NDT uses the newly proposed CSFPN module for feature fusion. CSFPN is a weighted bi-directional feature pyramid network integrating Convolutional Block Attention Module (CBAM). Compared to CenterNet with different modules, and some state-of-the-art methods, the proposed CenterNet-NDT achieves a greater mAP of 90.23% on the IN-ACCC dataset. The proposed automatic internal defect detection system is verified to be effective and robust by lab experiments and has been repeatedly applied in actual ACCC transmission line inspection tasks to reduce the safety hazards of wire breakage.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true


---

