---
title: Intelligent Bearing Fault Diagnosis Based on Scaled Ramanujan Filter Banks in Noisy Environments
summary: This paper is under review by IEEE TIM.
tags:
- Signal Processing
- Fault Diagnosis
- Deep Learning

date: "2019-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: The framework
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

Based on the Ramanujan Filter Banks (RFB) in the field of biological signal processing 

Abstract--- Bearing fault diagnosis plays an essential role in the maintenance of rotating machines in industries. Challenges posed in developing an effective and robust bearing fault diagnosis method include the essential complexity of vibration data and the external interference caused by the data collection. This study develops an intelligent data-driven method for bearing fault diagnosis in noisy environments, consisting of the feature transformation of vibration data and fault recognition based on transformed features. Firstly, an extension of the Ramanujan filter banks (RFB) method, Scaled-RFB, is introduced to suppress the noises and convert original time series vibration data into representative RGB images. Next, a strip convolutional neural network (Strip-CNN) is developed with strip convolution to recognize the health condition of bearings based on the obtained RGB images. Two vibration datasets collected from Soochow University and a public data source are utilized to validate the effectiveness and robustness of the proposed method individually. Six levels of Gaussian noises are separately added into the two datasets to further demonstrate the performance of the proposed method in noisy environments. Compared with six benchmarking methods, the proposed method can achieve the best performance on bearing fault diagnosis in most scenarios and shows promising performance on datasets with a higher noise level. When the signal-noise ratio (SNR) is    -10    dB, the average    **Precision   ,    Recall   , and    F1    scores of the proposed method on both datasets are at least    51.79%   ,    52.49%   , and    52.47%    higher than benchmarking methods, respectively.** 

At present, a periodic estimation method in the field of biological signal processing is introduced into bearing fault diagnosis, and some improvements are made, and neural networks are designed according to the characteristics of this feature, and better diagnostic results are obtained.

- The Ph.D.'s original plan was to follow the current tutor' reading, so the pace of work was slower. The instructor used to do methodology, so hopefully I can use machine learning to open up new tracks in my application. The thesis is mainly guided by the tutor's sister-in-law, who is not much involved in the process. (Because force majeure tutors do not have places, so want to go abroad to read)

- Do a lot of useless work in the early stage, because everyone's thinking is constantly adjusting, such as starting to feel that some simple machine learning algorithms are OK, as long as the final result is good; So it took a long time to finish writing, and in the process stepped on a lot of pits, so that many algorithms are now at least no problem in their use.

- Proposed Scaled-RFB method based on the RFB and designed Strip-CNN to achieve better

  fault diagnosis performance than benchmarks in noisy environments

- Next will consider the anomaly detection when anomalous samples are absent, and deal with

  the presence of periodic noise (signal components have fluctuations in period)





