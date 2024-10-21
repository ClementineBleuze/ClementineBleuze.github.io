---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---
{% include base_path %}

## CNP : A Corpus of annotated Claims found in NLP Papers

A corpus containing 15M+ sentences extracted from 100k+ NLP papers (ACL Anthology, ArXiv), enriched with : 

- *claim category* annotations (i.e. "contribution" claim, "result" claim, "impact" claim, etc.)
- *sentence-level* and *aspect-level* certainty (see [the work of Jiaxin Pei and David Jurgens](https://github.com/Jiaxin-Pei/Certainty-in-Science-Communication))
- *linguistic-level* annotations (counts of POS tags, named entities, etc.) conducted with spaCy

As well as : 

- metadata for all 100k+ papers
- XML files parsed from PDF files of ArXiv papers (using [GROBID](https://github.com/kermitt2/grobid))

The main data files of the corpus are available on [HuggingFace](https://github.com/kermitt2/grobid), and complementary code and materials can be found on [GitHub](https://github.com/ClementineBleuze/claims-in-NLP). To learn more about the corpus, the analyses that were conducted on it, and the motivation behind its creation, see [Analysing Claims in NLP Research : A NLP4NLP Approach (M2 thesis)]({{ BASE_PATH }}/files/M2-thesis.pdf).
