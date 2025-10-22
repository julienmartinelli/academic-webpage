---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Reactmine, a search algorithm for inferring chemical reaction networks from time series data
subtitle: 'Inferring chemical reaction networks (CRN) from concentration time series is a challenge encouragedby the growing availability of quantitative temporal data at the cellular level. This motivates thedesign of algorithms to infer the preponderant reactions between the molecular species observed ina given biochemical process, and build CRN structure and kinetics models. Existing ODE-basedinference methods such as SINDy resort to least square regression combined with sparsity-enforcingpenalization, such as Lasso. However, we observe that these methods fail to learn sparse modelswhen the input time series are only available in wild type conditions, i.e. without the possibility toplay with combinations of zeroes in the initial conditions. We present a CRN inference algorithmwhich enforces sparsity by inferring reactions in a sequential fashion within a search tree of boundeddepth, ranking the inferred reaction candidates according to the variance of their kinetics on theirsupporting transitions, and re-optimizing the kinetic parameters of the CRN candidates on the wholetrace in a final pass. We show that Reactmine succeeds both on simulation data by retrievinghidden CRNs where SINDy fails, and on two real datasets, one of fluorescence videomicroscopyof cell cycle and circadian clock markers, the other one of biomedical measurements of systemiccircadian biomarkers possibly acting on clock gene expression in peripheral organs, by inferringpreponderant regulations in agreement with previous model-based analyses.'
summary: ''
authors:
- Julien Martinelli
- Jeremy Grignard
- Sylvain Soliman
- Annabelle Ballesta
- François Fages
tags: []
categories: []
date: '2022-09-06'
# lastmod: 2021-08-22T16:08:09+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
# publishDate: '2020-08-22T14:08:08.216557Z'
publication_types:
- 1
abstract: ''
publication: "*Preprint*"
url_pdf: "files/hal_2022.pdf"
---
