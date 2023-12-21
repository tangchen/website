---
title: Identifying and Avoiding Data Leakage Issues When Using Machine Learning in Organizational Research
draft: false
# summary: An example of using the in-built project page.
# tags:
#   - Deep Learning
date: '2023-12-21T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: ''

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Machine learning (ML) is increasingly used in organizational research (Putka et al., 2018). However, researcher degrees of freedom and lack of knowledge regarding best practices for ML may reduce replicability (Epskamp, 2019; Wenzel & Quaquebeke, 2017). One of the most common, yet subtle, problems in ML is data leakage (Kaufman et al., 2012; Yarkoni & Westfall, 2017). Data leakage happens when the information about the outcome variable “leaks” into the model training process, and such information is not available when the trained model model is later used to make predictions on new data (Ambroise & McLachlan, 2002). Researchers in other fields of psychology have demonstrated that the success of ML is sometimes illusory because of leakage (e.g., Shim et al., 2021). Data leakage often happens unexpectedly and can be hard to detect (Hastie et al. 2009). The current project describes two overarching forms of leakage, uses simulated data to demonstrate how leakage causes upwardly biased model performance estimates, and delineates the likely manifestations of leakage and how to prevent them.