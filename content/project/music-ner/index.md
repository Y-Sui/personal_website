---
title: Automatic Knowledge Graph Generation
summary: Learning Deep Features towards Automation of Knowledge Graph Generation.
tags:
- NLP
date: "2020-03-27T00:00:00Z"
weight: 40

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
url_pdf: "uploads/JCSC.pdf"
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
Knowledge graph generation (KGG) aims at generating a knowledge graph from enormous amounts of unstructured sources. Once unstructured information is stored in a graph-structured format, it becomes easier to access and utilize. In this paper, we propose an automatic knowledge graph generation method based on an efficient contextual model. It is composed of layered convolutional neural networks (CNN) and attentionbased bidirectional LSTM layers. The model achieves similar performance compared to the RoBERTa (pre-trained model) but is time conserving and is lighter. In addition, we propose a framework to enrich the constructed KG with external high-quality sources using relation linking. The refined knowledge graph is visualized based on Neo4j. Our experiments highlight that our method achieves a few points of amelioration that can be readily applied to other similar domain fields.