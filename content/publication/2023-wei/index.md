---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Evaluating Shutdown Avoidance of Language Models in Textual Scenarios"
subtitle: ''
summary: 'We analyze in textual scenarios whether language models show the instrumental reasoning to avoid shutdown
'
authors:
- Teun van der Weij
- Simon Lermen
- Leon Lang
tags:
- Computer Science - Artificial Intelligence
categories: []
date: '2023-07-03'
lastmod: 2023-07-03T18:11:46+01:00
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
publishDate: '2023-07-03T17:11:46.691694Z'
publication_types:
- '1'
abstract: "Recently, there has been an increase in interest in evaluating large language models for emergent and dangerous capabilities. Importantly, agents could reason that in some scenarios their goal is better achieved if they are not turned off, which can lead to undesirable behaviors. In this paper, we investigate the potential of using toy textual scenarios to evaluate instrumental reasoning and shutdown avoidance in language models such as GPT-4 and Claude. Furthermore, we explore whether shutdown avoidance is merely a result of simple pattern matching between the dataset and the prompt or if it is a consistent behaviour across different environments and variations.
We evaluated behaviours manually and also experimented with using language models for automatic evaluations, and these evaluations demonstrate that simple pattern matching is likely not the sole contributing factor for shutdown avoidance. This study provides insights into the behaviour of language models in shutdown avoidance scenarios and inspires further research on the use of textual scenarios for evaluations."
publication: '*Safe and Trustworthy AI Workshop (ICLP 2023)*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2307.00787
---
