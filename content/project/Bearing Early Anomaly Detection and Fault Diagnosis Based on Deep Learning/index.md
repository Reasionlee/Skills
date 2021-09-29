---
title: Bearing Early Anomaly Detection and Fault Diagnosis Based on Deep Learning
summary: The main work during my master's degree.
tags:
- Signal Processing
- Abnormal Detection
- Fault Diagnosis
- Deep Learning

date: "2019-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: The structure
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Critical mechanical equipment usually serves under variable operating conditions with high load, making their bearings easy to fail. This project aims to detect and diagnose bearing failures to ensure the stable operation of equipment.

However, under the interference of strong noise and the modulation of variable operating conditions, the relationship between the collected data and the fault is unclear. And the data in the fault state is few or even missing, making the analysis more difficult.

Therefore, there are three research stages:

- **signal feature component extraction**: extract feature component from vibration data to using time-frequency analysis and modal decomposition algorithm
- **abnormal detection**: train the abnormal detection model using the one-class generation learning algorithm
- **fault diagnosis**: train the diagnosis model using multi-source domain transfer learning

This project is still in progress. 

