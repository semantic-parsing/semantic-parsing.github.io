---
layout: publication
title: "AMR Parsing as Graph Prediction with Latent Alignment"
authors: Chunchuan Lyu, Ivan Titov
conference: ACL
year: 2018
bibkey: lyu2018amr
additional_links:
   - {name: "PDF", url: "https://aclanthology.org/P18-1037.pdf"}
   - {name: "ArXiv", url: "https://arxiv.org/abs/1805.05286"}
   - {name: "Code", url: "https://github.com/ChunchuanLv/AMR_AS_GRAPH_PREDICTION"}
tags: ["amr"]
---
Abstract meaning representations (AMRs) are broad-coverage sentence-level semantic representations. AMRs represent sentences as rooted labeled directed acyclic graphs. AMR parsing is challenging partly due to the lack of annotated alignments between nodes in the graphs and words in the corresponding sentences. We introduce a neural parser which treats alignments as latent variables within a joint probabilistic model of concepts, relations and alignments. As exact inference requires marginalizing over alignments and is infeasible, we use the variational autoencoding framework and a continuous relaxation of the discrete alignments. We show that joint modeling is preferable to using a pipeline of align and parse. The parser achieves the best reported results on the standard benchmark (74.4% on LDC2016E25).
