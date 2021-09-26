---
layout: publication
title: "HybridQA: A Dataset of Multi-Hop Question Answering over Tabular and Textual Data"
authors: Wenhu Chen, Hanwen Zha, Zhiyu Chen, Wenhan Xiong, Hong Wang, William Wang
conference: EMNLP
year: 2019
bibkey: chen2019hybridqa
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/2004.07347v3"}
   - {name: "PDF", url: "https://aclanthology.org/2020.findings-emnlp.91.pdf"}
   - {name: "Website", url: "https://github.com/wenhuchen/HybridQA"}
tags: ["sql", "dataset"]
---
Existing question answering datasets focus on dealing with homogeneous information, based either only on text or KB/Table information alone. However, as human knowledge is distributed over heterogeneous forms, using homogeneous information alone might lead to severe coverage problems. To fill in the gap, we present HybridQA this https URL, a new large-scale question-answering dataset that requires reasoning on heterogeneous information. Each question is aligned with a Wikipedia table and multiple free-form corpora linked with the entities in the table. The questions are designed to aggregate both tabular information and text information, i.e., lack of either form would render the question unanswerable. We test with three different models: 1) a table-only model. 2) text-only model. 3) a hybrid model that combines heterogeneous information to find the answer. The experimental results show that the EM scores obtained by two baselines are below 20\%, while the hybrid model can achieve an EM over 40\%. This gap suggests the necessity to aggregate heterogeneous information in HybridQA. However, the hybrid model's score is still far behind human performance. Hence, HybridQA can serve as a challenging benchmark to study question answering with heterogeneous information.
