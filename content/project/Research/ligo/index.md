---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Laser beam position tracking for LIGO"
summary: "Deep learning for laser beam position tracking for LIGO interferometers."
authors: []
tags: ["Deep Learning", "Physics", "Hardware", "Undergraduate Project"]
categories: []
date: 2020-04-18T16:25:16+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Camera setup at viewport"
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
url_pdf: "../project/research/ligo/Final_Report.pdf"
url_slides: "../../project/research/ligo/presentation.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Abstract

LIGO  interferometers  used  to  detect  gravitational  waves  achieve  extremely  high sensitivity  through  precise  angular  control  of  suspended  optics  that  direct  the  laser beam.  A host of sensing techniques, ranging from optical levers and wavefront sensors to suitably positioned quadrant photodiodes are used to detect the angular position and deviation of optics. This work attempts to introduce the use of Gigabit Ethernet (GigE) cameras capturing images of light scattered from optics to determine the position of the laser beam on the optic.  A number of approaches based on tools from image processing are employed to discern the motion of the beam spot from video.  They are found to be unreliable and discarded in favour of convolutional neural networks which can, in theory, learn any complex, non-linear mapping.  These are trained on data generated at the 40m laboratory at Caltech and the results are analysed.

<!-- Would be nice to set up a gallery.	 -->