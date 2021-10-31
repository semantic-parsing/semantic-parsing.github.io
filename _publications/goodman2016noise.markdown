---
layout: publication
title: "Noise reduction and targeted exploration in imitation learning for Abstract Meaning Representation parsing"
authors: James Goodman, Andreas Vlachos, Jason Naradowsky
conference: ACL
year: 2016
bibkey: goodman2016noise
additional_links:
   - {name: "PDF", url: "https://aclanthology.org/P16-1001.pdf"}
   - {name: "Code", url: "https://github.com/hopshackle/dagger-AMR"}
tags: ["amr"]
---
Semantic parsers map natural language statements into meaning representations, and must abstract over syntactic phenomena, resolve anaphora, and identify word senses to eliminate ambiguous interpretations. Abstract meaning representation (AMR) is a recent example of one such semantic formalism which, similar to a dependency parse, utilizes a graph to represent relationships between concepts (Banarescu et al., 2013). As with dependency parsing, transition-based approaches are a common approach to this problem. However, when trained in the traditional manner these systems are susceptible to the accumulation of errors when they find undesirable states during greedy decoding. Imitation learning algorithms have been shown to help these systems recover from such errors. To effectively use these methods for AMR parsing we find it highly beneficial to introduce two novel extensions: noise reduction and targeted exploration. The former mitigates the noise in the feature representation, a result of the complexity of the task. The latter targets the exploration steps of imitation learning towards areas which are likely to provide the most information in the context of a large action-space. We achieve state-ofthe art results, and improve upon standard transition-based parsing by 4.7 F1 points.