---
title: Completion Percentage Over Expectation (CPOE) - NFL
summary: Stochastic Gradient Boosting to predict pass outcomes and find completion probability. NFL Analytics..
tags:
- Python
- NFL
- CPOE
date: "2020-11-21T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ROC Curve for Out-of-sample Predictions
  focal_point: Smart


links:
- icon: github
  icon_pack: fab
  name: View Project
  url: https://github.com/adriancm93/CPOE/blob/main/cpoe_model.ipynb

- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/adrian_stats




# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
In this project, I am attempting to predict the probabilty of a pass being completed. I will be using a classifying algorithm called Gradient Boosting for this purpose. Hoewver, even tho increasing accuracy of prediction is what I wan't for the mdoel to work properly, I am more interested in the estimated probabilities rather than the predicted outcome. Why? Because we will eb estimating the error in prediction (Outcome - Prob of completion) to estimate by how much a passer over or under predicted in a given pass. Finally, I will be estimating the mean residual (which we call CPOE) for each QB during the 2019.

Code here.

## **[Click here](https://github.com/adriancm93/CPOE/blob/main/cpoe_model.ipynb) to see project**
