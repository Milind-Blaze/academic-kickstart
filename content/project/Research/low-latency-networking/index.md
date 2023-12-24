---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Low-latency Networking"
summary: "Work focusing on low-latency networking for interactive applications"
authors: ["admin"]
tags: ["Low-latency Networking", "Project"]
categories: []
date: 2023-11-20T21:12:32+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "Networking challenge of interactive applications"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


Applications, especially interactive ones, require the underlying network to provide high throughput, low latency and high reliability to deliver satisfactory user experiences. While meeting all three requirements has proven challenging, _heterogeneous virtual channels_ (HVCs) have emerged in various networks which provide some subset of these at the expense of the rest. In this project, we explore how these HVCs can be used to boost application performance, why previous solutions can not do so effectively and what the features of a solution that does so are by analyzing the challenges and opportunities lying at the different layers of the network stack.
We also discuss making these solutions deployable and directions of future work.


This project involves addressing a number of questions-
- What are the right mechansims and algorithms for using HVCs to boost application performance?
- What does a system designed to use multiple HVCs look like?
- How can such a networking solution be integrated into applications like XR to boost performance and improve user experience?
- How do selfish users and applications behave when given access this powerful new network capability and what mechanism design is necessary to incentivise an optimal outcome?

The resulting work is below-

- [Boosting Application Performance Using HVCs](../../../publication/hotnets-2023)