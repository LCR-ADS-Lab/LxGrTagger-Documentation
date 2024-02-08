# LxGrTagger Annotation Guidelines

## Tagging scheme organization

The tagging scheme is organized into hierarchical structures:

- Structural type: The highest level of linguistic structure categorization.
    - Syntactic function: Classifies elements based on their function within the structural type.
        - **Complexity feature**: The focus of tagging, which includes:
            1. Descriptions: Detailed explanations of the complexity features.
            2. Tag: Guidelines on where to apply tags within the structure.
            3. Examples: Examples, where the target complexity feature is <ins>underlined</ins> and the tagging location is highlighted in **bold**.

## Documentation overview

- structual type 1: [finite dependent clauses](#structual-type-1-finite-dependent-clauses)
    - syntactic function 1: clause constituent adverbial
        - complexity feature 1: ...
    - syntactic function 2: [clause constituent verb complement](#syntactic-function-2-clause-constituent-verb-complement)
        - complexity feature 1: [verb + *that* complement clause](#complexity-feature-1-verb--that-complement-clause) (Week 5)
        - complexity feature 2: [verb + *wh*-complement clause](#complexity-feature-2-verb--wh-complement-clause-verb__wh) (Week 3)
    - syntactic function 3: [noun phrase (NP) constituent_NP modifier](#syntactic-function-3-noun-phrase-np-constituent_np-modifier)
    - syntactic function 4: [noun phrase constituent_NP complement](#syntactic-function-4-noun-phrase-constituent_np-complement) (Week 5)
    - syntactic function 5: [other phrase constituent_adjective complement](#syntactic-function-5-other-phrase-constituent_adjective-complement)
        - complexity feature 1: [adjective + *that*-complement clause](#complexity-feature-1-adjective--that-complement-clause) (Week 3)
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

##### Complexity feature 1: verb + *that*-complement clause (`V_that_comp`; `V_that_0`)

1. Descriptions

2. Tag
    - `V_that_comp` or `V_that_0` (with ZERO complementizer) is tagged on the **main verb** of the *that*-complement clause.

3. Examples
    - *I would hope <ins>that we can **have** more control over them.</ins>* (Kris' table)
    - (with ZERO complementizer) *yeah, I think <ins>I probably could.</ins>* (HS: included but no place to tag because we have no main verb?) (Kris' table)

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
    -  [passive] We tagged on the **passive**, not on the *be*-verb.
       -  *they knew <ins>what they were going to be **asked**.</ins>*
3. Examples
    - *I don't know <ins>how they **do** it.</ins>*
    - *She showed me <ins>where we should **plant** the tree.</ins>*
    - *He described <ins>what he **saw** at the event.</ins>*
    - *No one knows <ins>how long the journey will **take**.</ins>*
    - *"What I don't understand," she said, "is <ins>why they don't **let** me know anything.</ins>"* (p.193)
    - *that's <ins>how I **did** it.</ins>* (dataset)

#### Syntactic function 3: noun phrase (NP) constituent_NP modifier

*to be added soon*

#### Syntactic function 4: noun phrase constituent_NP complement (`N_that_comp`)
1. Descriptions (p.676)
    - Pre-predicate vs. Extraposed *that*-clauses:
        - Identifies two primary structures for *that*-clauses: (1) pre-predicate subject *that*-clauses and (2) extraposed *that*-clauses. In both cases, the *that*-clause is the logical subject of the sentence.
            - (1) Pre-predicate: *<ins>That Saints **managed** to cause an upset with nothing more than direct running and honest endeavour</ins> bodes well for Great Britain.*
            - (2) Extraposed: *Maybe it annoys them <ins>that you don't **fit** their image of a fairy princess.</ins>* = *<ins>That you don't **fit** their image of a fairy princess</ins> annoys them.*
    - Related Construction with NP Complement: It features a NP complement beginning with "the fact that".
        - e.g., *<ins>The fact that the medical technicians **were** available</ins> does not make the government's conduct any less offensive.*
        - In this structure, the *that*-clause is a complement to the NP "the fact", but typically shares a similar meaning with a pre-predicate *that*-clause (i.e., "the fact" can be omitted.)
    - NP complement clause (pp.644-645) (Reference; Not include this case)
        - There are two types of noun complement clauses: (1) *that*-clauses and (2) *to*-infinitive clauses.
            - (1) *that*-clauses*: *There were also [rumors] <ins>that Ford had now taken its stake up to the maximum 15 percent allowed.</ins>*
                - This does not count into the target tag here, because this not a complement for the verb, but a complement for the preceding noun (i.e., "adding some descriptive information about that noun", p.645).
                - In noun complement *that*-clauses, the complementizer "that" cannot be omitted.
            - (2) *to*-infinitive clauses: *These figures lead to an [expectation] <ins>that the main application area would **be** in the office environments.</ins>*" (From academic context)*

2. Tag
    - `N_that_comp` is tagged on the **main verb** of the *that*-complement clause.
3. Examples
    - *The fact <ins>that no tracer particles were **found**</ins> indicates that these areas are not a pathway…* (Kris' table)
    - *<ins>That he is **ranked** only No 4 in the world at the moment</ins> is due to the eccentricity of the system.*
    - *The observation <ins>that the species has **adapted** to urban environments</ins> challenges traditional views on wildlife habitat preferences.*
    - *<ins>That she **won** the award</ins> despite fierce competition speaks volumes about her talent.*
    - *The conclusion <ins>that global temperatures are **rising**</ins> faster than previously estimated is alarming.*
    - *<ins>That the project was **completed** under budget</ins> demonstrates efficient management and planning.*

#### Syntactic function 5: other phrase constituent_adjective complement
- An adjective complement serves to complete the meaning of an adjective

##### Complexity feature 1: adjective + *that*-complement clause
1. Descriptions
    - Adjectives link with *that*-complement clauses express (1) levels of certainty (e.g., *certain*, *confident*, *evident*), (2) emotional states (e.g., *annoyed*, *glad*, *sad*), or (3) judgment on events (e.g., *appropriate*, *good*, *important*) (Biber et al., 2007, p. 671).
    - We counted the examples with omitted *that* as *that* is frequently omitted in nominal *that*-clauses (pp.660-669).
        -  *I'm amazed <ins>you **know** him.</ins>* (dataset)
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
