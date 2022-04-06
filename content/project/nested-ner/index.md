---
title: Trigger-GNN
summary: A Trigger-Based Graph Neural Network for Nested Named Entity Recognition.
tags:
- NLP
date: "2020-03-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
url_pdf: "uploads/IJCNN.pdf"
#url_slides: "uploads/cf-kgqa.pptx"
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
slides: ""
---

**Abstract**:
Nested named entity recognition (NER) aims to identify the entity boundaries and recognize categories of the named entities in a complex hierarchical sentence. Some works have been done using character-level, word-level, or lexicon-level based models. However, such researches ignore the role of the complementary annotations. In this paper, we propose a trigger-based graph neural network (Trigger-GNN) to leverage the nested NER. It obtains the complementary annotation embeddings through entity trigger encoding and semantic matching, and tackle nested entity utilizing an efficient graph message passing architecture, aggregation-update mode. We posit that using entity triggers as external annotations can add in complementary supervision signals on the whole sentences. It helps the model to learn and generalize more efficiently and cost-effectively. Experiments show that the Trigger-GNN consistently outperforms the baselines on four public NER datasets, and it can effectively alleviate the nested NER.