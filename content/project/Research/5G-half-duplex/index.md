---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Half-duplex system design using USRP N321"
summary: ""
authors: ["admin"]
tags: ["5G", "Hardware"]
categories: []
date: 2020-08-05T15:42:44+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "USRP N321 front and rear panels"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Lab
  url: http://www.ee.iitm.ac.in/5g/
  icon_pack: fas
  icon: wifi

url_code: ""
url_pdf: "project/research/5g-half-duplex/usrp.pdf"
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

This work develops a half duplex system operating at 122.88 MSPS and transmitting data generated according to 5G NR standards using a Universal Software Radio Peripheral (USRP). A half duplex system can both transmit and receive but can not do both simultaneously. Instead, the system transmits for a period of time and receives for the remaining. Therefore, the system is designed in three stages- transmitter, receiver and then integration of the two. Once designed, the USRP is expected to work in parallel with the existing Keysight systems used at the Testbed if not replace them. In this work, USRP N321 by Ettus Research is used. The USRP is a software defined radio that uses software as a substitute for components implemented in hardware. The accompanying technical report details the procedures involved in setting up the USRP- the associated software, interfacing and verification of function. This document also discusses the design of a transmitter and receiver using GNU Radio and the associated challenges. The designed systems are tested using a Vector Signal Analyzer (VSA) and Vector Signal Generator (VSG) and data that adheres to the 5G standards is generated using MATLAB.