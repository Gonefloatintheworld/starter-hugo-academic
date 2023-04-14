---
title: 'Semantic stereo visual SLAM towards outdoor dynamic environment based on ORB-SLAM2'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guangming Song
  - et al

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2023-04-13T00:00:00Z'
doi: 'https://doi.org/10.1108/IR-09-2022-0236'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Industrial Robot*
publication_short: published in *Industrial Robot*

abstract: Purpose The prerequisite for most traditional visual simultaneous localization and mapping (V-SLAM) algorithms is that most objects in the environment should be static or in low-speed locomotion. These algorithms rely on geometric information of the environment and restrict the application scenarios with dynamic objects. Semantic segmentation can be used to extract deep features from images to identify dynamic objects in the real world. Therefore, V-SLAM fused with semantic information can reduce the influence from dynamic objects and achieve higher accuracy. This paper aims to present a new semantic stereo V-SLAM method toward outdoor dynamic environments for more accurate pose estimation. Design/methodology/approach First, the Deeplabv3+ semantic segmentation model is adopted to recognize semantic information about dynamic objects in the outdoor scenes. Second, an approach that combines prior knowledge to determine the dynamic hierarchy of moveable objects is proposed, which depends on the pixel movement between frames. Finally, a semantic stereo V-SLAM based on ORB-SLAM2 to calculate accurate trajectory in dynamic environments is presented, which selects corresponding feature points on static regions and eliminates useless feature points on dynamic regions. Findings The proposed method is successfully verified on the public data set KITTI and ZED2 self-collected data set in the real world. The proposed V-SLAM system can extract the semantic information and track feature points steadily in dynamic environments. Absolute pose error and relative pose error are used to evaluate the feasibility of the proposed method. Experimental results show significant improvements in root mean square error and standard deviation error on both the KITTI data set and an unmanned aerial vehicle. That indicates this method can be effectively applied to outdoor environments. Originality/value The main contribution of this study is that a new semantic stereo V-SLAM method is proposed with greater robustness and stability, which reduces the impact of moving objects in dynamic scenes.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false


---

