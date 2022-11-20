---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "VSSE: application to FOIA"
event: "UIUC ECE 407: Cryptography"
event_url: "https://soc1024.ece.illinois.edu/teaching/ececs407/fa21/" 
location: "UIUC"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "Using VSSE for FOIA compliance"
abstract: "The Freedom of Information Act (FOIA) allows citizens of a democracy to request access to documents- emails, memos, voice messages and so forth- concerning the functioning of the government. In this work, we address the problem of retrieving all the emails of a user- presumably an employee at a public institution obligated to respond to FOIA requests- containing a specific keyword while preserving the privacy of their emails. This is done using Verifiable Searchable Symmetric Encryption (VSSE). SSE schemes ensure that a curious Cloud Service Provider (CSP) learns nothing about the stored emails by suitably encrypting their plaintexts while maintaining the capability to search the stored data for specific tokens. The verifiability ensures that a CSP does not suppress a part of query response which is crucial to the FOIA setting. The result of our work is an open-source Python application that implements the desired VSSE scheme."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-12-08T16:00:00-06:00
# date_end: 2022-11-20T20:54:39+05:30
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: 2022-11-20T20:54:39+05:30

authors: ["admin"]
tags: ["Course Talk", "Course Project", "Cryptography"]

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
url_slides: "talk/vsse-foia/VSSE_application_to_FOIA.pdf"

url_code:
url_pdf: "talk/vsse-foia/ECE_407_report.pdf"
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
