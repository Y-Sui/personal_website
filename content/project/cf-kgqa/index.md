---
title: Causal Filter based KGQA
summary: Learning Causal Representations for Knowledge Graph-based Question Answering.
tags:
- NLP
date: "2020-03-27T00:00:00Z"
weight: 10

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
url_pdf: "uploads/cf-kgqa.pdf"
url_slides: "uploads/cf-kgqa.pptx"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
slides: ""
---

**Abstract**:
To improve the performance of knowledge graph-based question answering system (KGQA), several approaches have been developed to construct a semantic parser based on entity linking, relation identification and logical/numerical structure identification. However, existing methods arrive at answers only by maximizing the
data likelihood only on the sparse or imbalanced explicit relations, ignoring the potentially large number of latent relations, making KGQA suffer from a high level of spurious entity relations and missing link. In this paper, we propose a causal filter (CF) model for KGQA (CF-KGQA). It performs causal interference on the relation representation space to filter out the spurious entity relations in a
data-driven manner, and to comprehensively discover the disentangled latent factors to learn high-quality latent factors for producing more reasonable implicit latent relations. The model comprises a causal pairwise aggregator (AP) and a disentangled latent factor aggregator (AC). The former filters out most spurious entity relations inconsistent to their dense groups’ neighborhood, and
generates a causal pairwise matrix among all the candidate relations. The latter learns the representation of the latent relations via an encoder-decoder on the causal pairwise matrix from AP. It disconnects the latent factor and the causal confounder beneath the knowledge embedding space by causal intervention. Experiments indicate that our approach outperforms recent methods on four public real-world datasets, and its effectiveness in alleviating the spurious relations and missing link problems in KGQA.