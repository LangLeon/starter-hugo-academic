---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Information Decomposition Diagrams Applied beyond Shannon Entropy: A Generalization\
  \ of Hu's Theorem"
subtitle: ''
summary: 'We generalize information diagrams to functions beyond Shannon entropy, including Kolmogorov complexity and the generalization error from machine learning.
'
authors:
- Leon Lang
- Pierre Baudot
- Rick Quax
- Patrick Forré
tags:
- Computer Science - Information Theory
categories: []
date: '2022-01-01'
lastmod: 2022-02-27T18:11:46+01:00
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
publishDate: '2022-02-27T17:11:46.691694Z'
publication_types:
- '2'
abstract: "In information theory, one major goal is to find useful functions that\
  \ summarize the amount of information contained in the interaction of several random\
  \ variables. Specifically, one can ask how the classical Shannon entropy, mutual\
  \ information, and higher interaction information functions relate to each other.\
  \ This is formally answered by Hu's theorem, which is widely known in the form of\
  \ information diagrams: it relates disjoint unions of shapes in a Venn diagram to\
  \ summation rules of information functions; this establishes a bridge from set theory\
  \ to information theory. While a proof of this theorem is known, to date it was\
  \ not analyzed in detail in what generality it could be established. In this work,\
  \ we view random variables together with the joint operation as a monoid that acts\
  \ by conditioning on information functions, and entropy as the unique function satisfying\
  \ the chain rule of information. This allows us to abstract away from Shannon's\
  \ theory and to prove a generalization of Hu's theorem, which applies to Shannon\
  \ entropy of countably infinite discrete random variables, Kolmogorov complexity,\
  \ Tsallis entropy, (Tsallis) Kullback-Leibler Divergence, cross-entropy, submodular\
  \ information functions, and the generalization error in machine learning. Our result\
  \ implies for Chaitin's prefix-free Kolmogorov complexity that the higher-order\
  \ interaction complexities of all degrees are in expectation close to Shannon interaction\
  \ information. For well-behaved probability distributions on increasing sequence\
  \ lengths, this shows that asymptotically, the per-bit expected interaction complexity\
  \ and information coincide, thus showing a strong bridge between algorithmic and\
  \ classical information theory."
publication: '*arXiv e-prints*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2202.09393
---