---
title: Overview
nav_order: 2
---

# Overview
{: .no_toc }


The example below demonstrates the analysis of a sentence by LxGrTagger (See the [web demo](https://kristopherkyle.pythonanywhere.com/)).

![Alt text](https://lcr-ads-lab.github.io/LxGrTagger-Documentation/example.png)

Each token is placed in its own row, with columns describing the token’s form and syntactic function. Here is a brief explanation of the key columns:

- [Complexity (cx) tags](/LxGrTagger-Documentation/docs/cx%20tags/): Details about the complexity tags. For instance, you may see tags like `nn+npremod` (a noun used as a noun-phrase premodifier) or `finitecls+rel` (a finite relative clause).
- [Fine-grained tags](/LxGrTagger-Documentation/docs/fgrd%20tags/):
   - *main tag*: Corresponds to POS tags (e.g., *nn* for nouns, *jj* for adjectives).  
   - *cat1-9*: Each of these columns provides more specific morphological or syntactic information. For example, *cat1* may indicate number or pronoun type in *nn*.



