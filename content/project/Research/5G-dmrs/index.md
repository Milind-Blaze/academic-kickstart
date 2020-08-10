---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Channel Estimation Using PDSCH DMRS "
summary: "Work to generate multi-port, multi-symbol downlink DMRS and receive the same in the presence of a TDL channel"
authors: ["admin"]
tags: ["5G"]
categories: []
date: 2020-08-05T15:42:58+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Resource grid for different DMRS configurations"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Milind-Blaze/EE6143_2020/tree/master/Assignment6"
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

## Summary

DMRS symbols are generated according to the specifications in Section 7.4 of TS 38.211. This includes generation of DMRS symbols for either single or multiple ports, different configuration types, different types of PDSCH mapping and different types of resource allocation. Random M-QAM data is used to populate the empty subcarriers before transmission through a TDL channel (see TR 38.901). The received DMRS symbols are used to estimate the channel. The simulation supports multiple receive antennas as well. A comparison is made of the actual and estimated channel coefficients using suitable visualizations. 

This work was completed as a part of the course [EE6143](https://github.com/Milind-Blaze/EE6143_2020) at IIT Madras.
