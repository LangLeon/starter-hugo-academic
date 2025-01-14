---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Factored space models: Towards causality between levels of abstraction'
subtitle: ''
summary: 'We develop a new foundation for a theory of causality, based on factored space models'
authors:
- Scott Garrabrant
- Matthias Georg Mayer
- Magdalena Wache
- Leon Lang
- Sam Eisenstat
- Holger Dell
tags:
- Computer Science - Causality
categories: []
date: '2024-12-20'
lastmod: 2024-12-20T18:11:46+01:00
featured: false
draft: false

slides:
- example

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-12-20T17:11:46.691694Z'
publication_types:
- '3'
abstract: "Causality plays an important role in understanding intelligent behavior, and there is a wealth of literature on mathematical models for causality, most of which is focused on causal graphs. Causal graphs are a powerful tool for a wide range of applications, in particular when the relevant variables are known and at the same level of abstraction. However, the given variables can also be unstructured data, like pixels of an image. Meanwhile, the causal variables, such as the positions of objects in the image, can be arbitrary deterministic functions of the given variables. Moreover, the causal variables may form a hierarchy of abstractions, in which the macro-level variables are deterministic functions of the micro-level variables. Causal graphs are limited when it comes to modeling this kind of situation. In the presence of deterministic relationships there is generally no causal graph that satisfies both the Markov condition and the faithfulness condition. We introduce factored space models as an alternative to causal graphs which naturally represent both probabilistic and deterministic relationships at all levels of abstraction. Moreover, we introduce structural independence and establish that it is equivalent to statistical independence in every distribution that factorizes over the factored space. This theorem generalizes the classical soundness and completeness theorem for d-separation."
publication: '*arxiv e-prints*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2412.02579
---
