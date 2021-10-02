---
title: Temperature Control Scheme Design of Rice Storage Tank and Study on The Influence of Stacking Mode on Rice Storage at Low Temperature
summary: This project is funded by Agri-X.
tags:
- Design of Experiments
- ANOVA
- Copyright

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

# Temperature Control Scheme Design of Rice Storage Tank

## Sampling Points

According to the Taguchi experimental design method, the 18 sampling points in the tank are selected for temperature measurement: 

![points](points.png)

## Equipment

Anemograph (Testo 405i):

![Testo](Testo.png)

Temperature and humidity sensor (DS1023):

![DS1023](DS1023.png)

## Process

1. Analyse the measurement data using:
   - Bartlett test
   - ANOVA
   - F test
   - Other statistical methods
2. Evaluate the cooling effect according to the statistical differences 
3. Obtain the temperature control scheme under the given conditions

## Programming

The research results are programmed with VBA, so it can be run using Microsoft Excel.

The software has been copyrighted.

![example 1](example_1.jpg)

![example_2](example_2.png)

# Study on The Influence of Stacking Mode on Rice Storage at Low Temperature

## Equipment

### Containers

![container](container.png)

### Incubator

![Incubator](Incubator.jpg)

### Sensors

![sensor](sensor.jpg)

## Parameters

17 stacking modes are obtained from the combination of 9 parameters:

|  Stacking   | Centralization |  Location  |  Distance  | Partition  |    Height     | Dispersion |
| :---------: | :------------: | :--------: | :--------: | :--------: | :-----------: | :--------: |
| centralized |                | $\bigcirc$ |            |            |               |            |
|  dimidiate  |                |            | $\bigcirc$ |            |               |            |
|  dimidiate  |                | $\bigcirc$ | $\bigcirc$ |            |               |            |
| centralized |   $\bigcirc$   | $\bigcirc$ |            |            |               |            |
|  dimidiate  |                |            |            | $\bigcirc$ |               |            |
|  dimidiate  |                |            | $\bigcirc$ |            |               |            |
|             |                | $\bigcirc$ |            |            |      low      | $\bigcirc$ |
|             |                |            |            |            |  $\bigcirc$   |            |
|             |                | $\bigcirc$ |            |            | extremely low | $\bigcirc$ |

## Process

1. Model the rice’s temperature change over time based on the data of 30 sensors
2. Measure temperature’s statistical differences:
   - Normality test
   - ANOVA
   - Fisher LSD
3. Obtain the cooling effect of rice under different parameter combinations

