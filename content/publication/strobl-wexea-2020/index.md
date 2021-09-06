---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'WEXEA: Wikipedia EXhaustive Entity Annotation'
subtitle: ''
summary: ''
authors:
- Michael Strobl
- Amine Trabelsi
- Osmar R. Zaïane
tags: []
categories: []
date: '2020-05-01'
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
publishDate: '2021-09-06T11:29:40.306678Z'
publication_types:
- '1'
abstract: Building predictive models for information extraction from text, such as
  named entity recognition or the extraction of semantic relationships between named
  entities in text, requires a large corpus of annotated text. Wikipedia is often
  used as a corpus for these tasks where the annotation is a named entity linked by
  a hyperlink to its article. However, editors on Wikipedia are only expected to link
  these mentions in order to help the reader to understand the content, but are discouraged
  from adding links that do not add any benefit for understanding an article. Therefore,
  many mentions of popular entities (such as countries or popular events in history),
  or previously linked articles, as well as the article's entity itself, are not linked.
  In this paper, we discuss WEXEA, a Wikipedia EXhaustive Entity Annotation system,
  to create a text corpus based on Wikipedia with exhaustive annotations of entity
  mentions, i.e. linking all mentions of entities to their corresponding articles.
  This results in a huge potential for additional annotations that can be used for
  downstream NLP tasks, such as Relation Extraction. We show that our annotations
  are useful for creating distantly supervised datasets for this task. Furthermore,
  we publish all code necessary to derive a corpus from a raw Wikipedia dump, so that
  it can be reproduced by everyone.
publication: '*Proceedings of the 12th Language Resources and Evaluation Conference*'
url_pdf: https://aclanthology.org/2020.lrec-1.240
---
