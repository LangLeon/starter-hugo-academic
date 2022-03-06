---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning to Request Guidance in Emergent Communication
subtitle: ''
summary: 'We analyze the training behaviour of an agent that can ask for help. Doing this is costly, and so the agent learns to become more independent in familiar situations.'
authors:
- Benjamin Kolb
- Leon Lang
- Henning Bartsch
- Arwin Gansekoele
- Raymond Koopmanschap
- Leonardo Romor
- David Speck
- Mathijs Mul
- Elia Bruni
tags: []
categories: []
date: '2019-01-01'
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
publishDate: '2022-02-27T17:11:46.597618Z'
publication_types:
- '2'
abstract: "Previous research into agent communication has shown that a pre-trained\
  \ guide can speed up the learning process of an imitation learning agent. The guide\
  \ achieves this by providing the agent with discrete messages in an emerged language\
  \ about how to solve the task. We extend this one-directional communication by a\
  \ one-bit communication channel from the learner back to the guide: It is able to\
  \ ask the guide for help, and we limit the guidance by penalizing the learner for\
  \ these requests. During training, the agent learns to control this gate based on\
  \ its current observation. We find that the amount of requested guidance decreases\
  \ over time and guidance is requested in situations of high uncertainty. We investigate\
  \ the agent's performance in cases of open and closed gates and discuss potential\
  \ motives for the observed gating behavior."
publication: '*LANTERN@EMNLP-IJCNLP 2019 - Beyond Vision and LANguage: inTEgrating
  Real-World kNowledge, Proceedings*'
links:
- name: arXiv
  url: https://arxiv.org/abs/1912.05525
- name: Proceedings
  url: https://aclanthology.org/D19-64.pdf
---
