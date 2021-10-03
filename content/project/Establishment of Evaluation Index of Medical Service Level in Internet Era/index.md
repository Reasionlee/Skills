---
title: Establishment of Evaluation Index of Medical Service Level in Internet Era
summary: The project is funded by Innovative practice plan for College students (IPP17024).
tags:
- Evaluation Index

date: "2019-03-01T00:00:00Z"

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

# Background

There are many medical problems in China, for example, getting medical services is difficult and expensive. The government provides many prescriptions, including graded diagnoses, multi-site practices and so on. Here this project only concerns the plan with the internet background.

Since 2014, several companies have entered the Internet healthcare field. In March and July 2015, the State Council issued policy documents to encourage the development of Internet health care. Many mobile phone APPs and online hospitals are available now.

# Introduction

However, most of the current research focuses on the hospitals aiming to offer better medical services. Patients hardly know whether online medical service is a better solution or not for themselves. 

Without the guidance of scientific theory, it is difficult for patients to rationally analyze the advantages and disadvantages of their choice in a limited time. Therefore, this project will establish the evaluation index system for patients.

# Index

## Hospital

### Medical Level

| Hospital Level | Score | Standard Score |
| :------------: | :---: | :------------: |
|  Level III A   |  10   |      2.2       |
|  Level III B   |   9   |       2        |
|  Level III C   |   8   |      1.8       |
|   Level II A   |   6   |      1.3       |
|   Level II B   |   5   |      1.1       |
|   Level II C   |   4   |      0.9       |
|   Level I A    |   2   |      0.4       |
|   Level I B    |   1   |      0.2       |
|   Level I C    |   0   |      0.1       |

### Location

| Urban Hierarchy | Number | Score | Standard Score |
| :-------------: | :----: | :---: | :------------: |
|   first-tier    |   4    |  129  |      3.8       |
| new first-tier  |   15   |  90   |      2.7       |
|   second-tier   |   30   |  70   |      2.1       |
|   third-tier    |   70   |  30   |      0.9       |
|   fourth-tier   |   90   |  15   |      0.4       |
|   fifth-tier    |  129   |   4   |      0.1       |

## Patient

### Age

| Age Range | proportion (%) | Score | Standard Score |
| :-------: | :------------: | :---: | :------------: |
|   18~30   |       59       |  59   |       6        |
|   31~40   |       24       |  24   |      2.5       |
|   41~50   |       5        |   5   |      0.5       |
|   51~60   |       6        |   6   |      0.5       |
|   > 60    |       6        |   6   |      0.5       |

### Residence

| Urban Hierarchy | Number | Score | Standard Score |
| :-------------: | :----: | :---: | :------------: |
|   first-tier    |   4    |   4   |      0.1       |
| new first-tier  |   15   |  15   |      0.4       |
|   second-tier   |   30   |  30   |      0.9       |
|   third-tier    |   70   |  70   |      2.1       |
|   fourth-tier   |   90   |  90   |      2.7       |
|   fifth-tier    |  129   |  129  |      3.8       |

### Education

|      Education      | Accept the graded diagnoses (persons) | Reject the graded diagnoses (persons) | proportion (%) | Score | Standard Score |
| :-----------------: | :-----------------------------------: | :-----------------------------------: | :------------: | :---: | :------------: |
| $\leq$ high school  |                  184                  |                  94                   |       66       |  66   |      1.9       |
|   junior college    |                  432                  |                  45                   |       91       |  91   |      2.6       |
|    undergraduate    |                  377                  |                  45                   |       89       |  89   |      2.6       |
| $\geq$ postgraduate |                  45                   |                   0                   |      100       |  100  |      2.9       |

### Economic Condition

| Monthly Income | proportion (%) | Score | Standard Score |
| :------------: | :------------: | :---: | :------------: |
|     < 2000     |     69.23      |  70   |       3        |
|   2000~4000    |     75.74      |  76   |      3.3       |
|   4000~6000    |     44.94      |  45   |       2        |
|     > 6000     |     38.71      |  39   |      1.7       |

### Opinions from Others

| Opinions from Others | Score |
| :------------------: | :---: |
|    not recommend     |  -4   |
|      no opinion      |   0   |
|      recommend       |   4   |
|   highly recommend   |   6   |

## Disease

### Type

|     Disease Type     | Score |   Disease Type    | Score |
| :------------------: | :---: | :---------------: | :---: |
|  infectious disease  |   5   |   acute disease   |  -1   |
|   chronic disease    |   9   | dangerous disease |  -3   |
| occupational disease |   3   | stubborn disease  |  -5   |
|   endemic disease    |   5   |  special disease  |  -3   |
|    mental disease    |   7   |  unknown disease  |  -7   |

### Degree

Take Parkinson's disease for example:

| Hoehn-Yahr Level | Score |
| :--------------: | :---: |
|        1         |   0   |
|       1.5        |   2   |
|        2         |   2   |
|       2.5        |   2   |
|        3         |   0   |
|        4         |   2   |
|        5         |   2   |

## Policy

### Policy Orientation

| Policy Orientation | Score |
| :----------------: | :---: |
|  stimulus policy   |  10   |

# Criterion

Simulation 120,000 times:

| Score  | Counts | Score  | Counts | Score  | Counts | Score  | Counts |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| **49** |   4    | **37** |  2167  | **25** |  6138  | **13** |  1984  |
| **48** |   9    | **36** |  2535  | **24** |  6283  | **12** |  1603  |
| **47** |   14   | **35** |  3069  | **23** |  6023  | **11** |  1203  |
| **46** |   37   | **34** |  3671  | **22** |  5784  | **10** |  917   |
| **45** |   87   | **33** |  4116  | **21** |  5519  | **9**  |  576   |
| **44** |  148   | **32** |  4466  | **20** |  4995  | **8**  |  377   |
| **43** |  266   | **31** |  4760  | **19** |  4518  | **7**  |  201   |
| **42** |  411   | **30** |  4925  | **18** |  4111  | **6**  |   93   |
| **41** |  585   | **29** |  5438  | **17** |  3683  | **5**  |   41   |
| **40** |  830   | **28** |  5538  | **16** |  3260  | **4**  |   20   |
| **39** |  1172  | **27** |  5667  | **15** |  2737  | **3**  |   3    |
| **38** |  1587  | **26** |  6029  | **14** |  2400  |        |        |

Suppose the expected referral rate is **20%**, then the expected number is 24000.

So the criterion is **32**:

|   Score   | Counts |
| :-------: | :----: |
|   > 33    | 20708  |
|    32     |  4466  |
| $\geq$ 32 | 25174  |

