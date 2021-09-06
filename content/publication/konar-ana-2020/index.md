---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ANA at SemEval-2020 Task 4: MUlti-task learNIng for cOmmonsense reasoNing
  (UNION)'
subtitle: ''
summary: ''
authors:
- Anandh Konar
- Chenyang Huang
- Amine Trabelsi
- Osmar R. Zaïane
tags: []
categories: []
date: '2020-12-01'
lastmod: 2021-09-06T12:29:40+01:00
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
publishDate: '2021-09-06T11:29:40.475828Z'
publication_types:
- '1'
abstract: In this paper, we describe our mUlti-task learNIng for cOmmonsense reasoNing
  (UNION) system submitted for Task C of the SemEval2020 Task 4, which is to generate
  a reason explaining why a given false statement is non-sensical. However, we found
  in the early experiments that simple adaptations such as fine-tuning GPT2 often
  yield dull and non-informative generations (e.g. simple negations). In order to
  generate more meaningful explanations, we propose UNION, a unified end-to-end framework,
  to utilize several existing commonsense datasets so that it allows a model to learn
  more dynamics under the scope of commonsense reasoning. In order to perform model
  selection efficiently, accurately, and promptly, we also propose a couple of auxiliary
  automatic evaluation metrics so that we can extensively compare the models from
  different perspectives. Our submitted system not only results in a good performance
  in the proposed metrics but also outperforms its competitors with the highest achieved
  score of 2.10 for human evaluation while remaining a BLEU score of 15.7. Our code
  is made publicly available.
publication: '*Proceedings of the Fourteenth Workshop on Semantic Evaluation*'
url_pdf: https://aclanthology.org/2020.semeval-1.45
---
