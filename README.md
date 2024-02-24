# LxGrTagger Annotation Guidelines

## Tagging scheme organization

The tagging scheme is organized into hierarchical structures:

- Structural type: The highest level of linguistic structure categorization.
    - Syntactic function: Classifies elements based on their function within the structural type.
        - **Complexity feature**: The focus of tagging, which includes:
            1. Descriptions: Detailed explanations of the complexity features.
            2. Tag: Guidelines on where to apply the tag (`TAG NAME`) within the structure.
            3. Examples: Examples, where the target complexity feature is <ins>underlined</ins> and the tagging location is highlighted in **bold**.

## Documentation overview

- structual type 1: [finite dependent clauses](#structual-type-1-finite-dependent-clauses)
    - syntactic function 1: [clause constituent adverbial](#syntactic-function-1-clause-constituent-adverbial)
        - complexity feature 1: [multiple adverbial alcuses](#complexity-feature-1-multiple-adverbial-clause) (W7)
    - syntactic function 2: [clause constituent verb complement](#syntactic-function-2-clause-constituent-verb-complement)
        - complexity feature 1: [verb + *that* complement clause](#complexity-feature-1-verb--that-complement-clause-v_that_comp-v_that_0) (W5)
        - complexity feature 2: [verb + *wh*-complement clause](#complexity-feature-2-verb--wh-complement-clause-verb__wh) (W3)
    - syntactic function 3: [noun phrase (NP) constituent_NP modifier](#syntactic-function-3-noun-phrase-np-constituent_np-modifier)
        - complexity feature 1: [noun + finite relative clause](#complexity-feature-1-noun--finite-relative-clause-finite_rel) (W6)
    - syntactic function 4: [noun phrase constituent_NP complement](#syntactic-function-4-noun-phrase-constituent-np-complement)
        - complexity feature 1: [noun + *that*-complement clause](#complexity-feature-1-noun--that-complement-clause-n_that_comp) (W5)
    - syntactic function 5: [other phrase constituent_adjective complement](#syntactic-function-5-other-phrase-constituent_adjective-complement)
        - complexity feature 1: [adjective + *that*-complement clause](#complexity-feature-1-adjective--that-complement-clause-adj_that_comp) (W3, 6)
        - complexity feature 2: [extraposed adjective + *that*-complement clause](#complexity-feature-2-extraposed-adjective--that-complement-clause-xtraposjjthatcompcls) (W6)
    - syntactic function 6: [other phrase constituent_prepositional complement](#syntactic-function-6-other-phrase-constituent_preposition-complement)
        - complexity feature 1: [preposition + *wh*-complement clause](#complexity-feature-1-preposition--wh-complement-clause-prep__wh) (W8)        
- structural type 2: [non-finite dependent clauses](#structual-type-2-non-finite-dependent-clauses)
- structural type 3: [dependent phrases (non-clausal)](#structual-type-3-dependent-phrases-non-clausal)


----

## Documentation

### Structual type 1: finite dependent clauses
A **finite** dependent clause includes a verb phrase that is characterized by a specific tense or modality (Biber et al., 2007, p. 193).

#### Syntactic function 1: clause constituent adverbial

*to be added soon*

##### Complexity feature 1: multiple adverbial clause (`finite_advl_cls`)

(NOTE-HS: The original name of the complexity feature was 'causative, conditional, concessive clause.' It has been changed to 'multiple adverbial clause' for convenient naming.)

1. Descriptions (Biber et al., p. 194)
    - Adverbial clauses serve the role of adverbs of the main clause, generally describing additional circumstances. 
    - Similar to adverbials in general, they are optional; flexibility in their positioning within the sentence (either the beginning, midding, or end)
    - They are marked by a subordinator (e.g., *because*, *although*, *if*... see p.85) that showing the relationship to the main clause.
2. Tag
    - `finite_advl_cls` is tagged on the **main verb** of the adverbial clause.
3. Examples
    - *She won't narc on me, <ins>because she **prides** herself on being a gangster</ins>.*
    - *Well, <ins>if I **stay** here,</ins> I'll have to leave early in the morning.*
    - *He couldn't see the stage, <ins>although he **stood** on his tiptoes</ins>.*
    - *<ins>Since we **had** some time to spare,</ins> we decided to visit the museum.*
    - *<ins>While I **appreciate** classical music,</ins> I often listen to rock when I'm working out.*
    - *They kept playing, <ins>until it **started** to rain</ins>.*
    

#### Syntactic function 2: clause constituent verb complement
- Verb complement clauses are dependent clauses that complete the meaning of a verb in a higher (main) clause (Biber et al., 2007, p. 658).
- For general explanation on verb complement, see [here](MoreDescriptions.md#1-verb-complement).
- There are four types of verb complement clauses: (1) *that*-clause, (2) *wh*-cluase, (3) *to*-infinitive clause, and (4) *ing*-clause.

| Sentence | Finite dependent | Verb complement |
|-----------------|---------------------------|-----------------|
| <ins>That the team won the championship</ins> was unexpected. | ✓ | ✓ |
| She finished her work <ins>before the deadline arrived</ins>. | ✓ |   |
| I thought <ins>that it looked good</ins>.                     | ✓ | ✓ | 
| He agreed <ins>to help with the project</ins>.                |   | ✓ | 
| She enjoys <ins>running in the morning</ins>.                 |   | ✓ |
| The idea <ins>to be implemented</ins> involves several steps. |   | ✓ |

##### Complexity feature 1: verb + *that*-complement clause (`V_that_comp`; `V_that_0`)

1. Descriptions (Biber et al., 2007, p. 661)
    - Post-predicate *that*-clauses controlled by verbs come in 3 main domains
        - **Mental verbs:** Related to cognition, include emotive/affective content (e.g *hope*)
        - **Speech act verbs:** Directly indicate speech occuring (e.g *say*)
        - **Other communication verbs:** Do not *necessarily* involve speech (e.g *show*)
    - Note the lack of an intermediary NP or *to* NP between verb & *that*-clause
    - Common verbs:
        - **Mental:** believe, feel, find, guess, know, see, think, assume, conclude
        - **Speech act:** say, admit, agree, announce, argue, bet, insist
        - **Other communication:** show, suggest, ensure, indicate, prove

3. Tag
    - `V_that_comp` or `V_that_0` (with ZERO complementizer) is tagged on the **main verb** of the *that*-complement clause.
4. Examples
    - *I didn't agree <ins>that he should be **compelled** to do singing.</ins>* (Biber et al, p. 661)
    - *I suggested <ins>that she **sit** down on the chair and wait</ins>.* (*Ibid* 662)
    - *I would hope <ins>that we can **have** more control over them.</ins>* (Kris' table)
    - (with ZERO complementizer) *yeah, I think <ins>I probably could.</ins>* (HS: included but no place to tag because we don't have main verb?) (Kris' table)
    - *I propose <ins>that Mary should be invited</ins>.* (Haegeman & Guéron, 1998, p.441)

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

##### Complexity feature 1: noun + finite relative clause (`finite_rel`)

1. Descriptions
    -  *to be added*
2. Tag
    - `finite_rel` is tagged on the **main verb** of the *that*- of *wh*- relative clause (also include the relative clause with deleted relative pronoun).
3. Examples
    -  *to be added*

#### Syntactic function 4: noun phrase constituent: NP complement 

- When discussing 'complement' with verb complement, it was explained that complement clauses are dependent clauses that complete the meaning of a verb.
- NP-**modifier** and NP-**complement** are often ambiguous (Biber et al., p.644).
- The following is a brief explanation of NP-complementation (Haegeman & Guéron, 1998, pp.440-441):
    - Verbs take a wide range of complements, including finite clauses, non-finite clauses, etc.
    - Nouns can select finite clauses as their complements as demonstrated in the following examples (For more examples, see [here](MoreDescriptions.md#2-NP-complement)):
        - *I propose <ins>that Mary should be **invited**</ins>.* (verb-complement)
        - *The proposal <ins>that Mary should be **invited**</ins> is preposterous.* (NP-complement)

##### Complexity feature 1: noun + *that*-complement clause (`N_that_comp`)

1. Descriptions 
    - NP complement clause (pp.644-645)
        - There are two types of noun complement clauses: (1) *that*-clauses and (2) *to*-infinitive clauses.
            - (1) *that*-clauses*: *There were also [rumors] <ins>that Ford had now taken its stake up to the maximum 15 percent allowed.</ins>*
                - Here, the *that*-clause is NOT a complement for the verb, but a complement for the preceding noun (i.e., "adding some descriptive information about that noun", p.645).
                - In noun complement *that*-clauses, the complementizer "that" CANNOT be omitted.

            -  (2) *to*-infinitive clauses: *You've been given [permission] <ins>to wear them.</ins>* (Note: this is NOT included in the tag, just for reference)

    - Nominal postmodifiers are different from NP complement clauses (p. 644)
        - *Peter reached out for the well-thumbed report <ins>that **lay** behind him on the cupboard top.</ins>* (Nominal postmodifier; NOT included >> should be "noun + finite relative clause")
        - *Other semiconductor stocks eased folluwing an industry trade group's [report] <ins>that its leading indicator **fell** in September.</ins>* (NP complement clause; included)

2. Tag
    - `N_that_comp` is tagged on the **main verb** of the *that*-complement clause.
3. Examples
    - *The fact <ins>that no tracer particles were **found**</ins> indicates that these areas are not a pathway…* (Kris' table)
    - *The observation <ins>that the species has **adapted** to urban environments</ins> challenges traditional views on wildlife habitat preferences.*
    - *The conclusion <ins>that global temperatures are **rising**</ins> faster than previously estimated is alarming.*

#### Syntactic function 5: other phrase constituent_adjective complement
- An adjective complement serves to complete the meaning of an adjective

##### Complexity feature 1: adjective + *that*-complement clause (`adj_that_comp`)

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

##### Complexity feature 2: extraposed adjective + *that*-complement clause (`xtrapos+jj+that+compcls`)

1. Descriptions
    - *to be added*
2. Tag
    - `xtrapos+jj+that+compcls` is tagged on the **main verb** of the *that*-complement clause.
3. Examples
    - *to be added*

#### Syntactic function 6: other phrase constituent_preposition complement
- A preposition complement serves to complete the meaning of ...

##### Complexity feature 1: preposition + *wh*-complement clause (`prep_+_wh`)

1. Descriptions
    - *to be added*
2. Tag
    - `prep_+_wh` is tagged on the **main verb** of the *wh*-complement clause.
3. Examples
    - *I’ll offer a suggestion <ins>for what we should **do**.</ins>*

### Structual type 2: non-finite dependent clauses
*to be added soon*

### Structual type 3: dependent phrases (non-clausal)
*to be added soon*


----

### References
- Biber, D., Johansson, S., Leech, G., Conrad, S., & Finegan, E. (2007). *Longman Grammar of Spoken and Written English (6th ed.).* Longman.

- Haegeman, L., & Guéron, J. (1998). *English grammar: A generative perspective (Vol. 12).* John Wiley & Sons.
