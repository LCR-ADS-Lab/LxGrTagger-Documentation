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
| Finite clause  | Adverbial                 | [`finitecls+advl`](1_structural%20type1/1_Syntactic%20function1.html#1-1-clause-constituent-adverbial) | *She finished her work <ins>before the deadline **arrived**</ins>.* |
| Finite clause | Verb complement           | [`thatcls+vcomp`](1_structural%20type1/2_Syntactic%20function2.html#1-2-1-verb--that-complement-clause) | *<ins>That the team **won** the championship</ins> was unexpected.* |
| Finite clause | Verb complement           | [`whcls+vcomp`](1_structural%20type1/2_Syntactic%20function2.html#1-2-2-verb--wh-complement-clause) | *I wonder <ins>what that could **be** about</ins>.* |
| Finite clause  | Noun phrase modifier      | [`finitecls+rel`](1_structural%20type1/3_Syntactic%20function3.html#1-3-noun-phrase-constituent-modifier) | *The idea <ins>which **comes** up with great frequency</ins> involves several steps.* |
| Finite clause  | Noun phrase complement    | [`thatcls+ncomp`](1_structural%20type1/4_Syntactic%20function4.html#1-4-noun-phrase-constituent-complement) | *The conclusion <ins>that global temperatures are **rising**</ins> is alarming.* |
| Finite clause  | Adjective complement      | [`thatcls+jcomp`](1_structural%20type1/5_Syntactic%20function5.html#1-5-other-phrase-constituent_adjective-complement) | *We’re happy <ins>that the hunger strike has **ended**</ins>.* |
| Finite clause | Adjective complement      | [`xtrapos+thatcls+jcomp`](1_structural%20type1/5_Syntactic%20function5.html#1-5-2-extraposed-adjective--that-complement-clause) | *It's horrible <ins>that he **put** up with Claire’s nagging</ins>.* |
| Finite clause | Preposition complement    | [`whcls+incomp`](1_structural%20type1/6_Syntactic%20function6.html#1-6-other-phrase-constituent_preposition-complement) | *She is interested in <ins>what you **believe**</ins>.* |
| Non-finite clause | Adverbial                 | [`tocls+advl`](2_structural%20type2/1_Syntactic%20function1.html#2-1-clause-constituent-adverbial) | *<ins>To **verify** this hypothesis</ins>, sections of fixed cells were examined.* |
| Non-finite clause | Adverbial                 | [`ingcls+advl`](2_structural%20type2/1_Syntactic%20function1.html#2-1-2-ing-clause-as-adverbial) | *<ins>**Running** along the beach</ins>, she found a rare shell.* |
| Non-finite clause  | Adverbial                 | [`edcls+advl`](2_structural%20type2/1_Syntactic%20function1.html#2-1-3-ed-clause-as-adverbial) | *The sky had grown leaden-grey, <ins>**tinged** with a glow somewhere between orange and violet</ins>.* |
| Non-finite clause | Verb complement           | [`tocls+vcomp`](2_structural%20type2/2_Syntactic%20function2.html#2-2-1-verb--to-complement-clause) | *I want <ins>to **hold** your hand</ins>.* |
| Non-finite clause | Verb complement           | [`ingcls+vcomp`](2_structural%20type2/2_Syntactic%20function2.html#2-2-2-verb--ing-complement-clause) | *I like <ins>**running** south Amazon running trail</ins>.* |
| Non-finite clause | Noun phrase modifier           | [`tocls+rel`](2_structural%20type2/3_Syntactic%20function3.html#2-3-1-noun--to-relative-clause) | *Where is the best place <ins>to **eat** dinner near me</ins>?* |
| Non-finite clause | Noun phrase modifier           | [`ingcls+rel`](2_structural%20type2/3_Syntactic%20function3.html#2-3-2-noun--ing-relative-clause) |  *The person <ins>**sitting** on the chair</ins> is my colleague.*|
| Non-finite clause | Noun phrase modifier           | [`edcls+rel`](2_structural%20type2/3_Syntactic%20function3.html#2-3-3-noun--ed-relative-clause) | *The book <ins>**published** last year</ins> won several awards.* |
| Non-finite clause | Noun phrase complement           | [`tocls+ncomp`](2_structural%20type2/4_Syntactic%20function4.html#2-4-1-noun--to-complement-clause) | *His decision <ins>to **leave** early</ins> surprised everyone.* |
| Non-finite clause | Adjective complement           | [`tocls+jcomp`](2_structural%20type2/4_Syntactic%20function4.html#2-5-1-adjective--to-complement-clause) | *He was determined <ins>to **find** out the truth</ins>.* |
| Non-finite clause | Adjective complement           | [`xtrapos+tocls+jcomp`](2_structural%20type2/4_Syntactic%20function4.html#2-5-2-extraposed-adjective--to-complement-clause) | *It is possible <ins>to **get** things back on track</ins>.* |
| Non-finite clause | Prepositional complement           | [`ingcls+incomp`](2_structural%20type2/4_Syntactic%20function4.html#2-6-1-preposition--ing-complement-clause) | *The process <ins>for **washing** dishes by hand is attached</ins>.* |
| Dependent phrase | Adverb phrase | [`rb+advl`](3_structural%20type3/1_Syntactic%20function1.html#3-1-1-adverb-phrase) | *The car entered a curved road <ins>**slowly**</ins>.* |
| Dependent phrase | Prepositional phrase | [`in+advl`](3_structural%20type3/1_Syntactic%20function1.html#3-1-1-adverb-phrase) | *He spoke <ins>**with** enthusiasm</ins>.* |
<<<<<<< Updated upstream
=======
| Dependent phrase | Noun phrase modifier | [`attr+npremod`](3_structural%20type3/2_Syntactic%20function2.html#3-2-1-attributive-adjectives-as-noun-pre-modifier) | *She had <ins>a really **cute** idea</ins>.* |
| Dependent phrase | Noun phrase modifier | [`nn+npremod`](3_structural%20type3/2_Syntactic%20function2.html#3-2-2-noun-as-noun-pre-modifier) | *I'm not into <ins>**coffee** cake</ins>.* |
| Dependent phrase | Noun phrase modifier | [`of+npostmod`](3_structural%20type3/2_Syntactic%20function2.html#3-2-3-of-phrases-as-noun-post-modifier) | *Do you know <ins>the name **of** this flower</ins>?* |
| Dependent phrase | Noun phrase modifier | [`in+npostmod`](3_structural%20type3/2_Syntactic%20function2.html#3-2-4-other-prepositional-phrases-as-noun-post-modifier) | *The competition is open to <ins>young people **under** the age of 18</ins>.* |
| Dependent phrase | Noun phrase modifier | [`appos+npostmod`](3_structural%20type3/2_Syntactic%20function2.html#3-2-5-appositive-noun-phrases-as-noun-post-modifier) | *<ins>The boss, John **Harris**</ins> is a passionate figure.* | 
| Dependent phrase | Adjective complement | [`in+jcomp`](3_structural%20type3/3_Syntactic%20function3.html#3-3-1-prepositional-phrases-as-adjective-complement) | *She was <ins>thrilled **with** her completion of the PhD program</ins>.* |
| Dependent phrase | Adjective/Adverb modifier | [`rb+jjrbmod`](3_structural%20type3/4_Syntactic%20function4.html#3-4-1-adverb-phrase-as-adjectiveadverb-modifier) | *The movie was <ins>**surprisingly** good</ins>.* |
>>>>>>> Stashed changes
