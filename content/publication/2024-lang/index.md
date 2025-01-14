---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'When Your AIs Deceive You: Challenges of Partial Observability in Reinforcement Learning from Human Feedback'
subtitle: ''
summary: 'We theoretically and empirically study safety issues of using RLHF with human evaluators that have limited information'
authors:
- Leon Lang
- Davis Foote
- Stuart Russell
- Anca Dragan
- Erik Jenner
- Scott Emmons
tags:
- Computer Science - Artificial Intelligence
categories: []
date: '2024-02-17'
lastmod: 2024-02-17T18:11:46+01:00
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
publishDate: '2024-02-17T17:11:46.691694Z'
publication_types:
- '1'
abstract: "Past analyses of reinforcement learning from human feedback (RLHF) assume that the human evaluators fully observe the environment. What happens when human feedback is based only on partial observations? We formally define two failure cases: deceptive inflation and overjustification. Modeling the human as Boltzmann-rational w.r.t. a belief over trajectories, we prove conditions under which RLHF is guaranteed to result in policies that deceptively inflate their performance, overjustify their behavior to make an impression, or both. Under the new assumption that the human's partial observability is known and accounted for, we then analyze how much information the feedback process provides about the return function. We show that sometimes, the human's feedback determines the return function uniquely up to an additive constant, but in other realistic cases, there is irreducible ambiguity. We propose exploratory research directions to help tackle these challenges, experimentally validate both the theoretical concerns and potential mitigations, and caution against blindly applying RLHF in partially observable settings."
publication: '*NeurIPS 2024*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2402.17747
- name: Reviews
  url: https://openreview.net/forum?id=XcbgkjWSJ7
- name: Video
  url: https://neurips.cc/virtual/2024/poster/94754
- name: Blogpost
  url: https://www.lesswrong.com/posts/DS3TTpCEFKduC8zPy/paper-blogpost-when-your-ais-deceive-you-challenges-with
- name: Podcast
  url: https://www.youtube.com/watch?v=rAywTFQsKGQ
- name: TAIS 2024
  url: https://www.youtube.com/watch?v=6n-kyGqgRvk&t=16560s
- name: Poster
  url: https://neurips.cc/media/PosterPDFs/NeurIPS%202024/94754.png?t=1732529619.851263
---
