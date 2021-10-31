---
layout: publication
title: "Getting the Most out of AMR Parsing"
authors: Chuan Wang, Nianwen Xue
conference: EMNLP
year: 2017
bibkey: wang2017getting
additional_links:
   - {name: "PDF", url: "https://aclanthology.org/D17-1129.pdf"}
tags: ["amr", "lstm"]
---
This paper proposes to tackle the AMR parsing bottleneck by improving two components of an AMR parser: concept identification and alignment. We first build a Bidirectional LSTM based concept identifier that is able to incorporate richer contextual information to learn sparse AMR concept labels. We then extend an HMM-based word-to-concept alignment model with graph distance distortion and a rescoring method during decoding to incorporate the structural information in the AMR graph. We show integrating the two components into an existing AMR parser results in consistently better performance over the state of the art on various datasets.
