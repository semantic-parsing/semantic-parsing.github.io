---
layout: publication
title: "Meta-Learning for Domain Generalization in Semantic Parsing"
authors: Bailin Wang, Mirella Lapata, Ivan Titov
conference: NAACL
year: 2021
bibkey: wang2021meta
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/2010.11988"}
   - {name: "PDF", url: "https://aclanthology.org/2021.naacl-main.33.pdf"}
tags: ["sql", "meta-learning", "cross-domain", "transformer"]
---
Recent work in crosslingual semantic parsing has successfully applied machine translation to localize accurate parsing to new languages. However, these advances assume access to high-quality machine translation systems, and tools such as word aligners, for all test languages. We remove these assumptions and study cross-lingual semantic parsing as a zero-shot problem without parallel data for 7 test languages (DE, ZH, FR, ES, PT, HI, TR). We propose a multi-task encoder-decoder model to transfer parsing knowledge to additional languages using only English-Logical form paired data and unlabeled, monolingual utterances in each test language. We train an encoder to generate language-agnostic representations jointly optimized for generating logical forms or utterance reconstruction and against language discriminability. Our system frames zero-shot parsing as a latent-space alignment problem and finds that pre-trained models can be improved to generate logical forms with minimal cross-lingual transfer penalty. Experimental results on Overnight and a new executable version of MultiATIS++ find that our zero-shot approach performs above back-translation baselines and, in some cases, approaches the supervised upper bound.
