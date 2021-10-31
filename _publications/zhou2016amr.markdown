---
layout: publication
title: "AMR Parsing with an Incremental Joint Model"
authors: Junsheng Zhou, Feiyu Xu, Hans Uszkoreit, Weiguang Qu, Ran Li, Yanhui Gu
conference: EMNLP
year: 2016
bibkey: zhou2016amr
additional_links:
   - {name: "PDF", url: "https://aclanthology.org/D16-1065.pdf"}
tags: ["amr"]
---
To alleviate the error propagation in the traditional pipelined models for Abstract Meaning Representation (AMR) parsing, we formulate AMR parsing as a joint task that performs the two subtasks: concept identification and relation identification simultaneously. To this end, we first develop a novel componentwise beam search algorithm for relation identification in an incremental fashion, and then incorporate the decoder into a unified framework based on multiple-beam search, which allows for the bi-directional information flow between the two subtasks in a single incremental model. Experiments on the public datasets demonstrate that our joint model significantly outperforms the previous pipelined counterparts, and also achieves better or comparable performance than other approaches to AMR parsing, without utilizing external semantic resources.
