---
title: Batch Scheduling Optimization of Dynamic Flexible Workshop Based on Memetic Algorithm
summary: This is my undergraduate project (thesis) for Business Administration.
tags:
- Batch Scheduling
- Memetic Algorithm

date: "2019-06-30T00:00:00Z"

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

# Introduction

With the increasingly fierce market competition, the profits of traditional manufacturing industries are gradually being compressed, and the original rough production model is no longer applicable. More and more enterprises are paying attention to production and management efficiency. For the production workshop, scheduling is a key factor affecting production efficiency, and reasonable scheduling can shorten the manufacturing period and reduce inventory. However, the job-shop scheduling problem is one of the typical NP-hard problems. It is difficult to find an exact solution with limited time and effort. Therefore, a large number of heuristic algorithms have been generated, and Memetic Algorithm is one of them. 

This paper selects the case of a production workshop of an enterprise. For the flexible job shop batch scheduling problem with random arrival of workpieces, the goal of minimizing the maximum completion time is to adopt dynamic batch division strategy. 

The mathematical model was designed based on constraints such as batch division, machine allocation, processing order, machining, die change and machining operations. According to the framework of Memetic Algorithm, a two-level coding method was adopted for batch division queue and processing sort queue. The differential evolution algorithm was used as the global search strategy to insert. Neighborhood search is a local search strategy, which is implemented by Python language. Compared with the same batch, unscheduled benchmark results, the solution results can save 16.4% processing time.



随着市场竞争的日趋激烈，传统制造业的利润逐渐被压缩，原先粗旷的生产模式不再适用，越来越多的企业开始重视生产和管理效率。对于生产车间来说，调度是影响生产效率的关键因素，合理的调度可以缩短制造期、减少库存。但是，实践证明，在有限的时间和精力下，难以求得作业车间调度问题的精确解。因此产生了大量启发式算法，文化基因算法便是其中之一。本文选取了某企业生产车间的案例，针对工件随机到达的柔性作业车间批量调度问题，以最小化最大完成时间为目标，采取动态批量划分策略，考虑了批量划分、机器分配、加工顺序、机器加工、换模及加工操作等约束条件，设计了数学规划模型，并根据文化基因算法的框架，对批量划分队列和加工排序队列采取了两级编码方式，以差分进化算法作为全局搜索策略，以insert邻域搜索为局部搜索策略，通过python语言进行了编程实现。与等批量、未调度的基准结果相比，求解得到的结果可以节约16.4%的加工时间。

