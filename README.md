# LxGrTagger Annotation Guidelines

## Structure

- Category?: A high-level classification of linguistic features? 
    - need to check the naming convention

- **Tag**: A specific annotation for LxGrTagger
    - Description (details about the linguistic features)
    - Tag (details about the tagging point? or tagging anchor?)

## Overview
- Category [1](#category-1-finite-dependent-clauses-complement-clauses): Finite Dependent Clauses 
    - Tag [1](#tag-1-verb-wh-complement-clause-verb_wh). Verb + *wh*-complement clause (`verb_+_wh`)
    - Tag [2](#tag-2-adjective-that-complement-clause-adj_that_comp) Adjective + that complement clause (`adj_that_comp`)
- Category [2](#category-2-non-finite-dependent-clauses): Non-finite Dependent Clauses 
- Category [3](#category-3-dependent-phrases-non-clausal): Dependent Phrases (non-clausal)

----

### Category 1: Finite Dependent Clauses / Complement clauses

- Finite dependent clauses (Biber et al., 2007, p. 193)
    - A **finite** dependent clause includes a verb phrase that is characterized by a specific tense or modality.
         
- Complement clauses (Biber et al., 2007, p. 658)
    - Complement clauses are dependent clauses that complete the meaning of a verb or adjective in a higher (main) clause.
    - Define complement? 
    - There are four types of complement clauses: (1) *that*-clause, (2) *wh*-cluase, (3) *to*-infinitive clause, and (4) *ing*-clause.

- Examples:

| Sentence | Finite Dependent | Complement |
|-----------------|---------------------------|-----------------|
| <ins>That the team won the championship</ins> was unexpected. | ✓ | ✓ |
| She finished her work <ins>before the deadline arrived</ins>. | ✓ |   |
| I thought <ins>that it looked good</ins>.                     | ✓ | ✓ | 
| He agreed <ins>to help with the project</ins>.                |   | ✓ | 
| She enjoys <ins>running in the morning</ins>.                 |   | ✓ |
| The idea <ins>to be implemented</ins> involves several steps. |   | ✓ |


The following tags are included in this category:
- [1] [Tag 1](#tag-1-verb-wh-complement-clause-verb_wh). Verb + *wh*-complement clause (`verb_+_wh`)


### Tag 1. Verb + *wh*-complement clause (`verb_+_wh`)

#### Descriptions 
- Refer to Biber et al. (2007), p. 683
- *wh*-clauses can be either dependent (1) interrogative clauses or (2) nominal relative clauses.
- Common *wh*-words: what, who, where, when, why, 'how', and whether
- Types:
  - **Interrogative Clauses**: Used with verbs like *ask* and *wonder* to present indirect questions.
    - Example: I wonder <ins>what that could be about</ins>.
  - **Nominal Relative Clauses**: Can be paraphrased by a general head noun modified by the *wh*-clause (e.g., </ins>Whoever solves this problem</ins> will be successful => </ins>The person who solves this problem</ins> will be successful.)
    - Example: <ins>What baffles me</ins> is how few of them can spell. 


#### Tag
- **verb_+_wh** is tagged on the **main verb** of the complement clause.

Examples:
- *I don't know <ins>how they **do** it.</ins>*


### Tag 2. Adjective + that complement clause (adj_that_comp)






### Category 2: Non-finite Dependent Clauses
*to be added soon*

### Category 3: Dependent Phrases (non-clausal)
*to be added soon*


----

### References
Biber, D., Johansson, S., Leech, G., Conrad, S., & Finegan, E. (2007). Longman Grammar of Spoken and Written English (6th ed.). Longman.
