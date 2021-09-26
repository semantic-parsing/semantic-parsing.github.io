---
layout: publication
title: "Did You Ask a Good Question? A Cross-Domain Question Intention Classification Benchmark for Text-to-SQL"
authors: Yusen Zhang, Xiangyu Dong, Shuaichen Chang, Tao Yu, Peng Shi, Rui Zhang
conference:
year: 2020
bibkey: zhang2020did
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/2010.12634v1"}
   - {name: "Website", url: "https://github.com/chatc/TriageSQL"}
tags: ["sql", "cross-domain", "dataset"]
---
Neural models have achieved significant results on the text-to-SQL task, in which most current work assumes all the input questions are legal and generates a SQL query for any input. However, in the real scenario, users can input any text that may not be able to be answered by a SQL query. In this work, we propose TriageSQL, the first cross-domain text-to-SQL question intention classification benchmark that requires models to distinguish four types of unanswerable questions from answerable questions. The baseline RoBERTa model achieves a 60% F1 score on the test set, demonstrating the need for further improvement on this task. Our dataset is available at this URL: https://github.com/chatc/TriageSQL
