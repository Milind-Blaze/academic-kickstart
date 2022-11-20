---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Source Separation"
summary: "A study of NMF and its use in audio source separation."
authors: ["admin"]
tags: ["SPandComms", "Undergraduate Project"]
categories: []
date: 2020-04-19T22:00:07+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Milind-Blaze/source_separation"
url_pdf: "../../../project/research/source-separation/report.pdf"
url_slides: ""
# url_video: "https://www.youtube.com/watch?v=vc-WlAqv17c"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

{{< youtube vc-WlAqv17c >}}


## Abstract

Blind signal separation or source separation refers to the separation of each of the individual sources from a mixture of sources given little or no prior information about the source components. This has been a topic of great study and several techniques relying on matrix methods exist for this task. Non-negative matrix factorization is one such technique popularly used for its representational power and ease of implementation. In this work, NMF is introduced, the central algorithm based on multiplicative update rules is discussed and a comparison is drawn between local implementations of the algorithm and the implementation in scikit-learn. Following this, variants of the original algorithm utilising priors of sparseness and temporal continuity are used to perform source separation on mixtures of musical notes. The variation of the signal to noise ratio (SNR) is studied for different variants of NMF, different windows and window lengths and different weights of the sparseness and temporal continuity cost functions.