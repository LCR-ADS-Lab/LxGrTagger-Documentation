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

| Structural type | Syntactic function        | Complexity feature (`Tag`)                          | Examples                                                    |
|-----------------|---------------------------|------------------------------------------------------|-------------------------------------------------------------|
| Finite          | Adverbial                 | [`finitecls+advl`](1_structural%20type1/1_Syntactic%20function1.html#1-1-clause-constituent-adverbial) | *She finished her work <ins>before the deadline **arrived**</ins>.* |
| Finite          | Verb complement           | [`thatcls+vcomp`](1_structural%20type1/2_Syntactic%20function2.html#1-2-1-verb--that-complement-clause) | *<ins>That the team **won** the championship</ins> was unexpected.* |
| Finite          | Verb complement           | [`whcls+vcomp`](1_structural%20type1/2_Syntactic%20function2.html#1-2-2-verb--wh-complement-clause) | *I wonder <ins>what that could **be** about</ins>.* |
| Finite          | Noun phrase modifier      | [`finitecls+rel`](1_structural%20type1/3_Syntactic%20function3.html#1-3-noun-phrase-constituent-modifier) | *The idea <ins>which **comes** up with great frequency</ins> involves several steps.* |
| Finite          | Noun phrase complement    | [`thatcls+ncomp`](1_structural%20type1/4_Syntactic%20function4.html#1-4-noun-phrase-constituent-complement) | *The conclusion <ins>that global temperatures are **rising**</ins> is alarming.* |
| Finite          | Adjective complement      | [`thatcls+jcomp`](1_structural%20type1/5_Syntactic%20function5.html#1-5-other-phrase-constituent_adjective-complement) | *We’re happy <ins>that the hunger strike has **ended**</ins>.* |
| Finite          | Adjective complement      | [`xtrapos+thatcls+jcomp`](1_structural%20type1/5_Syntactic%20function5.html#1-5-2-extraposed-adjective--that-complement-clause) | *It's horrible <ins>that he **put** up with Claire’s nagging</ins>.* |
| Finite          | Preposition complement    | [`whcls+incomp`](1_structural%20type1/6_Syntactic%20function6.html#1-6-other-phrase-constituent_preposition-complement) | *She is interested in <ins>what you **believe**</ins>.* |
| Non-finite      | Adverbial                 | [`tocls+advl`](2_structural%20type2/1_Syntactic%20function1.html#2-1-clause-constituent-adverbial) | *<ins>To **verify** this hypothesis</ins>, sections of fixed cells were examined.* |
| Non-finite      | Adverbial                 | [`ingcls+advl`](2_structural%20type2/1_Syntactic%20function1.html#2-1-2-ing-clause-as-adverbial) | *<ins>**Running** along the beach</ins>, she found a rare shell.* |
| Non-finite      | Adverbial                 | [`edcls+advl`](2_structural%20type2/1_Syntactic%20function1.html#2-1-3-ed-clause-as-adverbial) | *The sky had grown leaden-grey, <ins>**tinged** with a glow somewhere between orange and violet</ins>.* |
| Non-finite      | Verb complement           | [`tocls+vcomp`](2_structural%20type2/2_Syntactic%20function2.html#2-2-1-verb--to-complement-clause) | *I want <ins>to **hold** your hand</ins>.* |
| Non-finite      | Verb complement           | [`ingcls+vcomp`](2_structural%20type2/2_Syntactic%20function2.html#2-2-2-verb--ing-complement-clause) | *I like <ins>**running** south Amazon trail</ins>.* |
| Non-finite      | Noun phrase modifier           | [`tocls+rel`](2_structural%20type2/3_Syntactic%20function3.html#2-3-1-noun--to-relative-clause) | *Where is the best place <ins>to **eat** dinner near me</ins>?* |
| Non-finite      | Noun phrase modifier           | [`ingcls+rel`](2_structural%20type2/3_Syntactic%20function3.html#2-3-2-noun--ing-relative-clause) |  *The person <ins>**sitting** on the chair</ins> is my colleague.*|
| Non-finite      | Noun phrase modifier           | [`edcls+rel`](2_structural%20type2/3_Syntactic%20function3.html#2-3-3-noun--ed-relative-clause) | *The book <ins>**published** last year</ins> won several awards.* |
| Non-finite      | Noun phrase complement           | [`tocls+ncomp`](2_structural%20type2/4_Syntactic%20function4.html#2-4-1-noun--to-complement-clause) | *His decision <ins>to **leave** early</ins> surprised everyone* |
