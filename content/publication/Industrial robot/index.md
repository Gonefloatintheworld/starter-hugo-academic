---
title: 'Semantic stereo visual SLAM towards outdoor dynamic environment based on ORB-SLAM2'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guangming Song
  - et al.

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Industrial Robot*
publication_short: writing in *Industrial Robot*

abstract: Purpose –The prerequisite for most traditional visual simultaneous localization and mapping (V-SLAM) algorithms is that most objects in the environment should be static or in low locomotion. These algorithms rely on geometric information of the environment and restrict the application scenarios with dynamic objects. Semantic segmentation can be used to extract deep features and semantic information from images to identify dynamic objects in the real world. Therefore, V-SLAM fused with semantic information can reduce the error from dynamic objects and achieve higher accuracy. This paper presents a new semantic stereo SLAM method towards outdoor dynamic environment for accurate pose estimation.  Design/methodology/approach –First, Deeplabv3+ semantic segmentation model is adopted to recognize semantic information about objects in the dynamic outdoor scenes. Second, a method that combines prior semantic knowledge to determine the motion state of moveable objects is proposed. which depends on the pixel movement between frames. Last, a semantic stereo SLAM based on ORB-SLAM2 to calculate accurate trajectory in dynamic environments is presented, which selects corresponding feature points on static regions and eliminates useless feature points on dynamic regions. Findings –The method is successfully performed on the public datasets KITTI and self-collected datasets in the real world. The V-SLAM system extracts the semantic information and tracks feature points steadily in dynamic environments. Originality/value – The main contribution of this study is to propose a new semantic stereo V-SLAM method with greater robustness and stability, which reduces the impact of moving objects in dynamic scenes.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false


---

