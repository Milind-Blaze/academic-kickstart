---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Music Mood Annotation"
summary: "Creation of a dataset and implementation of deep learning techniques for automatic music emotion recognition."
authors: ["admin"]
tags: ["Deep Learning", "SPandComms", "Undergraduate Project"]
categories: []
date: 2020-04-19T22:00:18+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Emotion labels on valence-arousal plane"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Lab
  url: https://www.researchgate.net/institution/Fraunhofer_Institute_for_Digital_Media_Technology_IDMT/department/Semantic_Music_Technologies_Research_Group
  icon_pack: fas
  icon: file-audio

url_code: ""
url_pdf: "../../project/research/music-mood-annotation/report.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Abstract

Automatic  annotation  of  music  with  emotion labels is a challenging task owing to the subjectivity of emotions associated with music. Much of this work focuses on creating a sizeable dataset with sufficient annotations that tackles the issue of  subjectivity  adequately.  By  combining  pre-existing  datasets with discrete and continuous emotion labels, a dataset with 79 hours worth of audio is obtained. All the audios are represented as  points  in  the  valence-arousal  plane  and  are  then  clustered into four classes for the purpose of developing classifiers. CNNs which use mel spectrograms as inputs are the primary focus of this  work.  A  maximum  accuracy  of  50.89%  is  obtained  in  the four-class  classification  task  with  accuracies  in  the  individual tasks  of  valence  and  arousal  classifications  being  70.8%  and 71.7%  respectively.