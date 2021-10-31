---
layout: publication
title: "An AMR Aligner Tuned by Transition-based Parser"
authors: Yijia Liu, Wanxiang Che, Bo Zheng, Bing Qin, Ting Liu
conference: EMNLP
year: 2018
bibkey: liu2018an
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/1810.03541"}
   - {name: "PDF", url: "https://aclanthology.org/D18-1264.pdf"}
   - {name: "Code", url: "https://github.com/Oneplus/tamr"}
tags: ["amr"]
---
In this paper, we propose a new rich resource enhanced AMR aligner which produces multiple alignments and a new transition system for AMR parsing along with its oracle parser. Our aligner is further tuned by our oracle parser via picking the alignment that leads to the highest-scored achievable AMR graph. Experimental results show that our aligner outperforms the rule-based aligner in previous work by achieving higher alignment F1 score and consistently improving two open-sourced AMR parsers. Based on our aligner and transition system, we develop a transition-based AMR parser that parses a sentence into its AMR graph directly. An ensemble of our parsers with only words and POS tags as input leads to 68.4 Smatch F1 score.
