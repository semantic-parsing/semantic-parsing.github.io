---
layout: publication
title: "AMR Parsing as Sequence-to-Graph Transduction"
authors: Sheng Zhang, Xutai Ma, Kevin Duh, Benjamin Van Durme
conference: ACL
year: 2019
bibkey: zhang2019amr
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/1905.08704"}
   - {name: "PDF", url: "https://aclanthology.org/P19-1009.pdf"}
   - {name: "Code", url: "https://github.com/sheng-z/stog"}
tags: ["amr", "transformer"]
---
We propose an attention-based model that treats AMR parsing as sequence-to-graph transduction. Unlike most AMR parsers that rely on pre-trained aligners, external semantic resources, or data augmentation, our proposed parser is aligner-free, and it can be effectively trained with limited amounts of labeled AMR data. Our experimental results outperform all previously reported SMATCH scores, on both AMR 2.0 (76.3% on LDC2017T10) and AMR 1.0 (70.2% on LDC2014T12).