---
title: Multi-Fidelity Bayesian Optimization with Unreliable Information Sources
event: Machine Learning Coffee Seminar 
event_url: https://fcai.fi/calendar/2023/3/28/julien-martinelli-multi-fidelity-bayesian-optimization-with-unreliable-information-sources

location: Aalto University, Espoo, Finland
#address:
#  street: Campus Universitaire, La Source
#  city: Orléans
#  postcode: '45067'
#  country: France

# summary: An example talk using Academic's Markdown slides feature.
abstract: "Bayesian optimization (BO) is a powerful framework for optimizing black-box, expensive-to-evaluate functions. Over the past decade, many algorithms have been proposed to integrate cheaper, lower-fidelity approximations of the objective function into the optimization process, with the goal of converging towards the global optimum at a reduced cost. This task is generally referred to as multi-fidelity Bayesian optimization (MFBO). However, MFBO algorithms can lead to higher optimization costs than their vanilla BO counterparts, especially when the low-fidelity sources are poor approximations of the objective function, therefore defeating their purpose. To address this issue, we propose rMFBO (robust MFBO), a methodology to make any GP-based MFBO scheme robust to the addition of unreliable information sources. rMFBO comes with a theoretical guarantee that its performance can be bound to its vanilla BO analog, with high controllable probability. We demonstrate the effectiveness of the proposed methodology on a number of numerical benchmarks, outperforming earlier MFBO methods on the most unreliable sources. We expect rMFBO to be particularly useful for including the varying expertise of human experts in Bayesian optimization processes in a reliable manner."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-05-15T14:00:00Z"
# date_end: "2019-05-27T17:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
url_code: ""
url_pdf: ""
url_slides: "files/mlcs_2023.pdf"
url_poster: "files/aistats_poster_2023.pdf"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#- internal-project

# Enable math on this page?
math: true
---
