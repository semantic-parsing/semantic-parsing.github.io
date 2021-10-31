---
layout: publication
title: "Neural AMR: Sequence-to-Sequence Models for Parsing and Generation"
authors: Ioannis Konstas, Srinivasan Iyer, Mark Yatskar, Yejin Choi, Luke Zettlemoyer
conference: ACL
year: 2017
bibkey: konstas2017neural
additional_links:
   - {name: "ArXiv", url: "https://arxiv.org/abs/1704.08381"}
   - {name: "Code", url: "https://github.com/sinantie/NeuralAmr"}
tags: ["amr"]
---
Sequence-to-sequence models have shown strong performance across a broad range of applications. However, their application to parsing and generating text usingAbstract Meaning Representation (AMR)has been limited, due to the relatively limited amount of labeled data and the non-sequential nature of the AMR graphs. We present a novel training procedure that can lift this limitation using millions of unlabeled sentences and careful preprocessing of the AMR graphs. For AMR parsing, our model achieves competitive results of 62.1SMATCH, the current best score reported without significant use of external semantic resources. For AMR generation, our model establishes a new state-of-the-art performance of BLEU 33.8. We present extensive ablative and qualitative analysis including strong evidence that sequence-based AMR models are robust against ordering variations of graph-to-sequence conversions.
