# LxGrTagger Annotation Guidelines

- This project is under the [LCR-ADS lab](https://lcr-ads-lab.github.io/LCR-ADS-Home/) at the University of Oregon's Linguistics Department, led by Dr. Kristopher Kyle.

- We are currently developing tag descriptions and detailed annotation guidelines for complexity features for [LxGrTagger](https://github.com/kristopherkyle/LxGrTgr). For some of the more complex examples, we have added a `Discussions` section below the corresponding tags based on the discussions between the team at the University of Oregon and scholars from Northern Arizona University (Many thanks to Douglas Biber, Jesse Egbert, and Randi Reppen for providing valuable insights!). 

- In the process of constructing the guidelines, we primarily refer to the *Longman Grammar of Spoken and Written English (6th ed.)* by Biber et al. (2007), paraphrasing the contents and specifying the referred pages. When citing other works, we include both the references and the specific page numbers.

## Tagging scheme

The tagging scheme is organized into hierarchical structures:

- Structural **type**: The highest level of linguistic structure categorization.
    - Syntactic **function**: Classifies elements based on their function within the structural type.
        - **Complexity feature**: The focus of tagging, which includes:
            1. Descriptions: Detailed explanations of the complexity features.
            2. Tag: Guidelines on where to apply the tag (`TAG NAME`) within the structure.
            3. Examples: Examples, where the target complexity feature is <ins>underlined</ins> and the tagging location is highlighted in **bold**.
            4. Discussions

## Quick examples overview

| Examples                                                    | Structural type | Syntactic function        | Complexity feature (`Tag`)                          |
|-------------------------------------------------------------|-----------------|---------------------------|------------------------------|
| *She finished her work <ins>before the deadline arrived</ins>.* | Finite | Adverbial | [`finite_advl_cls`](1_structural%20type1/1_Syntactic%20function1.html#1-1-clause-constituent-adverbial) |
| *<ins>That the team won the championship</ins> was unexpected.* | Finite | Verb complement | [`V_that_comp`](1_structural%20type1/2_Syntactic%20function2.html#1-2-1-verb--that-complement-clause) |
| *I wonder <ins>what that could be about</ins>.* | Finite | Verb complement | [`verb_+_wh`](1_structural%20type1/2_Syntactic%20function2.html#1-2-2-verb--wh-complement-clause) |
| *The idea <ins>which needs be implemented</ins> involves several steps.* | Finite | Noun phrase modifier | [`finite_rel`](1_structural%20type1/3_Syntactic%20function3.html#1-3-noun-phrase-constituent-modifier) |
| *The conclusion <ins>that global temperatures are rising</ins> is alarming.* | Finite | Noun phrase complement | [`N_that_comp`](1_structural%20type1/4_Syntactic%20function4.html#1-4-noun-phrase-constituent-complement) |
| *We’re happy <ins>that the hunger strike has ended</ins>.* | Finite | Adjective complement | [`adj_that_comp`](1_structural%20type1/5_Syntactic%20function5.html#1-5-other-phrase-constituent_adjective-complement) |
| *It's horrible <ins>that he put up with Claire’s nagging</ins>.* | Finite | Adjective complement | [`xtrapos+jj+that+compcls`](1_structural%20type1/5_Syntactic%20function5.html#1-5-2-extraposed-adjective--that-complement-clause) |
| *She is interested in <ins>what you believe</ins>.* | Finite | Preposition complement | [`prep_+_wh`](1_structural%20type1/6_Syntactic%20function6.html#1-6-other-phrase-constituent_preposition-complement) |
| *<ins>To verify this hypothesis</ins>, sections of fixed cells were examined.* | Non-finite | Adverbial | [`to_advl_cls`](2_structural%20type2/1_Syntactic%20function1.html#2-1-clause-constituent-adverbial) |
| *<ins>Running along the beach</ins>, she found a rare shell.* | Non-finite | Adverbial | [`ing_advl_cls`](2_structural%20type2/1_Syntactic%20function1.html#2-1-2-ing-clause-as-adverbial) |
| *The sky had grown leaden-grey, <ins>tinged with a glow somewhere between orange and violet</ins>.* | Non-finite | Adverbial | [`ed_advl_cls`](2_structural%20type2/1_Syntactic%20function1.html#2-1-3-ed-clause-as-adverbial) |

