---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The Perils of Optimizing Learned Reward Functions: Low Training Error Does Not Guarantee Low Regret'
subtitle: ''
summary: 'We theoretically analyze to what extent an error in a learned reward function translates into regret of resulting policies'
authors:
- Lukas Fluri
- Leon Lang
- Allesandro Abate
- Patrick Forré
- David Krueger
- Joar Skalse
tags:
- Computer Science - Artificial Intelligence
categories: []
date: '2024-06-22'
lastmod: 2024-06-22T18:11:46+01:00
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
publishDate: '2024-11-17T17:11:46.691694Z'
publication_types:
- '3'
abstract: "In reinforcement learning, specifying reward functions that capture the intended task can be very challenging. Reward learning aims to address this issue by learning the reward function. However, a learned reward model may have a low error on the training distribution, and yet subsequently produce a policy with large regret. We say that such a reward model has an error-regret mismatch. The main source of an error-regret mismatch is the distributional shift that commonly occurs during policy optimization. In this paper, we mathematically show that a sufficiently low expected test error of the reward model guarantees low worst-case regret, but that for any fixed expected test error, there exist realistic data distributions that allow for error-regret mismatch to occur. We then show that similar problems persist even when using policy regularization techniques, commonly employed in methods such as RLHF. Our theoretical results highlight the importance of developing new ways to measure the quality of learned reward models."
publication: '*arxiv e-prints*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2406.15753
---
