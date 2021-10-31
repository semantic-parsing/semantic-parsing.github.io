---
layout: publication
title: "CAMR at SemEval-2016 Task 8: An Extended Transition-based AMR Parser"
authors: Chuan Wang, Sameer Pradhan, Xiaoman Pan, Heng Ji, Nianwen Xue
conference: SemEval
year: 2016
bibkey: wang2016camr
additional_links:
   - {name: "PDF", url: "https://aclanthology.org/S16-1181.pdf"}
   - {name: "Code", url: "https://github.com/c-amr/camr"}
tags: ["amr"]
---
This paper describes CAMR, the transitionbased parser that we use in the SemEval-2016 Meaning Representation Parsing task. The main contribution of this paper is a description of the additional sources of information that we use as features in the parsing model to further boost its performance. We start with our existing AMR parser and experiment with three sets of new features: 1) rich named entities, 2) a verbalization list, 3) semantic role labels. We also use the RPI Wikifier to wikify the concepts in the AMR graph. Our parser achieves a Smatch F-score of 62% on the official blind test set.
