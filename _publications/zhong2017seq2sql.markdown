---
layout: publication
title: "Seq2SQL: Generating Structured Queries from Natural Language using Reinforcement Learning"
authors: Victor Zhong, Caiming Xiong, Richard Socher
conference:
year: 2017
bibkey: zhong2017seq2sql
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/1709.00103"}
   - {name: "Website", url: "https://github.com/salesforce/WikiSQL"}
tags: ["sql", "cross-domain", "dataset", "reinforcement-learning"]
---
A significant amount of the world's knowledge is stored in relational databases. However, the ability for users to retrieve facts from a database is limited due to a lack of understanding of query languages such as SQL. We propose Seq2SQL, a deep neural network for translating natural language questions to corresponding SQL queries. Our model leverages the structure of SQL queries to significantly reduce the output space of generated queries. Moreover, we use rewards from in-the-loop query execution over the database to learn a policy to generate unordered parts of the query, which we show are less suitable for optimization via cross entropy loss. In addition, we will publish WikiSQL, a dataset of 80654 hand-annotated examples of questions and SQL queries distributed across 24241 tables from Wikipedia. This dataset is required to train our model and is an order of magnitude larger than comparable datasets. By applying policy-based reinforcement learning with a query execution environment to WikiSQL, our model Seq2SQL outperforms attentional sequence to sequence models, improving execution accuracy from 35.9% to 59.4% and logical form accuracy from 23.4% to 48.3%.
