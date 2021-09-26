---
layout: publication
title: "A Pilot Study of Text-to-SQL Semantic Parsing for Vietnamese"
authors: Anh Tuan Nguyen, Mai Hoang Dao, Dat Quoc Nguyen
conference: EMNLP
year: 2020
bibkey: nguyen2020a
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/2010.01891v1"}
   - {name: "PDF", url: "https://aclanthology.org/2020.findings-emnlp.364.pdf"}
   - {name: "Website", url: "https://github.com/VinAIResearch/ViText2SQL"}
tags: ["sql", "cross-domain", "dataset"]
---
Semantic parsing is an important NLP task. However, Vietnamese is a low-resource language in this research area. In this paper, we present the first public large-scale Text-to-SQL semantic parsing dataset for Vietnamese. We extend and evaluate two strong semantic parsing baselines EditSQL (Zhang et al., 2019) and IRNet (Guo et al., 2019) on our dataset. We compare the two baselines with key configurations and find that: automatic Vietnamese word segmentation improves the parsing results of both baselines; the normalized pointwise mutual information (NPMI) score (Bouma, 2009) is useful for schema linking; latent syntactic features extracted from a neural dependency parser for Vietnamese also improve the results; and the monolingual language model PhoBERT for Vietnamese (Nguyen and Nguyen, 2020) helps produce higher performances than the recent best multilingual language model XLM-R (Conneau et al., 2020).
