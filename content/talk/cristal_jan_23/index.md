---
title: Reactmine - a search algorithm for inferring chemical reaction networks from time series data
event: Séminaire d'unité CriStAL
event_url: http://bioss-cnrs.fr/manif/biossia_201905/biossia201905.html

location: Centre de Recherche en Informatique, Signal et Automatique de Lille, Lille, France
#address:
#  street: Campus Universitaire, La Source
#  city: Orléans
#  postcode: '45067'
#  country: France

# summary: An example talk using Academic's Markdown slides feature.
abstract: "Inferring chemical reaction networks (CRN) from time series data is a challenge encouraged by the growing availability of quantitative temporal data at the cellular level.
This motivates the design of algorithms to infer the preponderant reactions between the molecular species observed in a given biochemical process, and help to build CRN model structure and
kinetics. Existing ODE-based inference methods such as SINDy resort to least square regression
combined with sparsity-enforcing penalization, such as Lasso. However, when the input time
series are only available in wild type conditions in which all reactions are present, we observe
that current methods fail to learn sparse models. We present Reactmine, a CRN learning algorithm which enforces sparsity by inferring
reactions in a sequential fashion within a search tree of bounded depth, ranking the inferred reaction candidates according to the variance of their kinetics, and re-optimizing the CRN kinetic
parameters on the whole trace in a final pass to rank the inferred CRN candidates. We first
evaluate its performance on simulation data from a benchmark of hidden CRNs, together with
algorithmic hyperparameter sensitivity analyses, and then on two sets of real experimental data:
one from protein fluorescence videomicroscopy of cell cycle and circadian clock markers, and one
from biomedical measurements of systemic circadian biomarkers possibly acting on clock gene
expression in peripheral organs. We show that Reactmine succeeds both on simulation data by
retrieving hidden CRNs where SINDy fails, and on the two real datasets by inferring reactions
in agreement with previous studies"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-01-03T10:30:00Z"
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
url_slides: "files/cristal_2023.pdf"
url_video: ""

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
