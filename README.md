# LxGrTagger Annotation Guidelines

## Tagging scheme organization

The tagging scheme is organized into hierarchical structures:

- Structural type: The highest level of linguistic structure categorization.
    - Syntactic function: Classifies elements based on their function within the structural type.
        - **Complexity Feature**: The focus of tagging, which includes:
            1. Descriptions: Detailed explanations of the complexity features.
            2. Tag Placement: Guidelines on where to apply tags within the structure.
            3. Examples: Examples, where the target complexity feature is <ins>underlined</ins> and the tagging location is highlighted in **bold**.

## Documentation overview

- structual type 1: [finite dependent clauses](#structual-type-1-finite-dependent-clauses)
    - syntactic function 1: clause constituent adverbial
        - complexity feature 1: ...
    - syntactic function 2: [clause constituent verb complement](#syntactic-function-2-clause-constituent-verb-complement)
        - complexity feature 1: verb + *that* complement clause
        - complexity feature 2: [verb + *wh*-complement clause](#complexity-feature-2-verb--wh-complement-clause-verb__wh) (Note: This is where we start from.)
    - syntactic function 3: noun phrase (NP) constituent_NP modifier
    - syntactic function 4: noun phrase constituent_NP complement
    - syntactic function 5: [other phrase constituent_adjective complement](#syntactic-function-5-other-phrase-constituent_adjective-complement)
        - complexity feature 1: [adjective + *that*-complement clause](#complexity-feature-1-adjective--that-complement-clause) (Note: Where we go next.)
    - syntactic function 6: other phrase constituent_prepositional complement
- structural type 2: [non-finite dependent clauses](#structual-type-2-non-finite-dependent-clauses)
- structural type 3: [dependent phrases (non-clausal)](#structual-type-3-dependent-phrases-non-clausal)

----

## Documentation

### Structual type 1: finite dependent clauses
A **finite** dependent clause includes a verb phrase that is characterized by a specific tense or modality (Biber et al., 2007, p. 193).

#### Syntactic function 1: clause constituent adverbial

#### Syntactic function 2: clause constituent verb complement
- Complement clauses are dependent clauses that complete the meaning of a verb or adjective in a higher (main) clause (Biber et al., 2007, p. 658).
- There are four types of complement clauses: (1) *that*-clause, (2) *wh*-cluase, (3) *to*-infinitive clause, and (4) *ing*-clause.

| Sentence | Finite dependent | Complement |
|-----------------|---------------------------|-----------------|
| <ins>That the team won the championship</ins> was unexpected. | ✓ | ✓ |
| She finished her work <ins>before the deadline arrived</ins>. | ✓ |   |
| I thought <ins>that it looked good</ins>.                     | ✓ | ✓ | 
| He agreed <ins>to help with the project</ins>.                |   | ✓ | 
| She enjoys <ins>running in the morning</ins>.                 |   | ✓ |
| The idea <ins>to be implemented</ins> involves several steps. |   | ✓ |

##### Complexity feature 1: verb + *that*-complement clause

##### Complexity feature 2: verb + *wh*-complement clause (`verb_+_wh`)
1. Descriptions (Biber et al., 2007, p. 683)
    - *wh*-clauses can be either dependent (1) interrogative clauses or (2) nominal relative clauses.
    - Common *wh*-words: what, who, where, when, why, 'how', and whether
    - Types:
        - Interrogative clauses: Used with verbs like *ask* and *wonder* to present indirect questions.
            - e.g., *I wonder <ins>what that could **be** about</ins>.*
        - Nominal relative clauses: Can be paraphrased by a general head noun modified by the *wh*-clause (e.g., *<ins>Whoever solves this problem</ins> will be successful.* => *The person who solves this problem will be successful.*)
            - e.g., *<ins>What **baffles** me</ins> is how few of them can spell.* 
2. Tag
    -  `verb_+_wh` is tagged on the **main verb** of the *wh*-complement clause.
3. Examples
    - *I don't know <ins>how they **do** it.</ins>*
    - *She showed me <ins>where we should **plant** the tree.</ins>*
    - *He described <ins>what he **saw** at the event.</ins>*
    - *No one knows <ins>how long the journey will **take**.</ins>*

#### Syntactic function 5: other phrase constituent_adjective complement
- An adjective complement serves to complete the meaning of an adjective

##### Complexity feature 1: adjective + *that*-complement clause
1. Descriptions
    - Adjectives link with *that*-complement clauses express (1) levels of certainty (e.g., *certain*, *confident*, *evident*), (2) emotional states (e.g., *annoyed*, *glad*, *sad*), or (3) judgment on events (e.g., *appropriate*, *good*, *important*) (Biber et al., 2007, p. 671).
2. Tag
    - `adj_that_comp` is tagged on the **main verb** of the *that*-complement clause.
3. Examples
    - *We’re happy <ins>that the hunger strike has **ended**.</ins>*
    - *I'm glad <ins>that I **found** you again.</ins>*
    - *It's nice <ins>that people **say** it to you.</ins>*

### Structual type 2: non-finite dependent clauses
*to be added soon*

### Structual type 3: dependent phrases (non-clausal)
*to be added soon*


----

### References
Biber, D., Johansson, S., Leech, G., Conrad, S., & Finegan, E. (2007). Longman Grammar of Spoken and Written English (6th ed.). Longman.
