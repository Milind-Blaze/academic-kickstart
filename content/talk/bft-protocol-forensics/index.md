---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "BFT Protocol Forensics"
event: "UIUC CS 598 FTD: Fault-Tolerant Distributed Algorithms"
event_url: "https://sites.google.com/view/cs598ftd/home"
location: "UIUC"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "Discussion of the paper BFT Protocol Forensics"
abstract: "In this work, we explore the idea of forensics for BFT protocols. BFT protocols are designed to solve consensus among n replicas as long as the number of Byzantine replicas or faults f is less than a threshold T. If there are more faults than T, either safety or liveness can be violated. Safety is violated when at least two honest replicas commit two different values. Forensics is a \"day after\" analysis, which asks, can we identify the Byzantine nodes responsible for this violation? More importantly, the analysis should be able to provide irrefutable proof of culpability of those nodes. So it is not enough that some honest nodes can identify the Byzantine nodes, knowing that they themselves are honest. In a real scenario, where we do not know which nodes are honest, forensics makes sense only if the honest nodes can put together a proof that shows the perpetrators of the protocol violation. Naturally, the proof can not depend on logs of all replicas, since Byzantine nodes can forge it. The best forensics would require logs of as few nodes as possible to prove culpability of as many Byzantine nodes as possible."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-04-22T13:00:00+06:00
# date_end: 2022-11-20T19:55:44+05:30
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2022-11-20T19:55:44+05:30

authors: ["admin"]
tags: ["BFT", "Course Project", "Course Talk"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: "talk/bft-protocol-forensics/bft_forensics.pdf"

url_code:
url_pdf: "talk/bft-protocol-forensics/CS598FTD_Spring_22_Report.pdf"
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
