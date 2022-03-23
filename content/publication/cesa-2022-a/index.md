---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Program to Build E(N)-Equivariant Steerable CNNs
subtitle: ''
summary: 'We propose a general method to implement equivariant convolutional neural networks and demonstrate it for 3D equivariant tasks. The implementation is based on the Wigner-Eckart theorem for steerable kernels.'
authors:
- Gabriele Cesa
- Leon Lang
- Maurice Weiler
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-02-27T18:11:46+01:00
featured: false
draft: false

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
publishDate: '2022-02-27T17:11:46.506325Z'
publication_types:
- '1'
abstract: Equivariance is becoming an increasingly popular design choice to build
  data efficient neural networks by exploiting prior knowledge about the symmetries
  of the problem at hand. Euclidean steerable CNNs are one of the most common classes
  of equivariant networks. While the constraints these architectures need to satisfy
  are understood, no practical method to parametrize them generally has been described
  so far, with most existing approaches tailored to specific groups or classes of
  groups. In this work, we generalize the Wigner-Eckart theorem proposed in Lang &
  Weiler (2021), which characterizes general G-steerable kernel spaces for compact
  groups G over their homogeneous spaces, to arbitrary G-spaces. This enables us to
  directly parameterize filters in terms of a band-limited basis on the base space,
  but also to easily implement steerable CNNs equivariant to a large number of groups.
  To demonstrate its generality, we instantiate our method on a large variety of isometry
  groups acting on the Euclidean space R^3. Our general framework allows us to build
  E(3) and SE(3)-steerable CNNs like previous works, but also CNNs with arbitrary
  G textless O(3)-steerable kernels. For example, we build 3D CNNs equivariant to
  the symmetries of platonic solids or choose G=SO(2) when working with 3D data having
  only azimuthal symmetries. We compare these models on 3D shapes and molecular datasets,
  observing improved performance by matching the model's symmetries to the ones of
  the data.
publication: '*International Conference on Learning Representations*'
links:
- name: Reviews
  url: https://openreview.net/forum?id=WE4qe9xlnQw
- name: Code
  url: https://github.com/QUVA-Lab/escnn
- name: Video
  url: https://recorder-v3.slideslive.com/#/share?share=63712&s=29adbadb-7392-470d-be5e-a6e7b07da0f4
---
