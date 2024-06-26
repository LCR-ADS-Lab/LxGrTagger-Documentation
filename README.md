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
        - complexity feature 1: [multiple adverbial clauses](#complexity-feature-1-multiple-adverbial-clause-finite_advl_cls) (W8)
    - syntactic function 2: [clause constituent verb complement](#syntactic-function-2-clause-constituent-verb-complement)
        - complexity feature 1: [verb + *that* complement clause](#complexity-feature-1-verb--that-complement-clause-v_that_comp-v_that_0) (W5) ✓
        - complexity feature 2: [verb + *wh*-complement clause](#complexity-feature-2-verb--wh-complement-clause-verb__wh) (W3) ✓
    - syntactic function 3: [noun phrase (NP) constituent_NP modifier](#syntactic-function-3-noun-phrase-np-constituent_np-modifier)
        - complexity feature 1: [noun + finite relative clause](#complexity-feature-1-noun--finite-relative-clause-finite_rel) (W6) ✓
    - syntactic function 4: [noun phrase constituent_NP complement](#syntactic-function-4-noun-phrase-constituent-np-complement)
        - complexity feature 1: [noun + *that*-complement clause](#complexity-feature-1-noun--that-complement-clause-n_that_comp) (W5) ✓
    - syntactic function 5: [other phrase constituent_adjective complement](#syntactic-function-5-other-phrase-constituent_adjective-complement)
        - complexity feature 1: [adjective + *that*-complement clause](#complexity-feature-1-adjective--that-complement-clause-adj_that_comp) (W3, 6)
        - complexity feature 2: [extraposed adjective + *that*-complement clause](#complexity-feature-2-extraposed-adjective--that-complement-clause-xtraposjjthatcompcls) (W6) ✓
    - syntactic function 6: [other phrase constituent_prepositional complement](#syntactic-function-6-other-phrase-constituent_preposition-complement)
        - complexity feature 1: [preposition + *wh*-complement clause](#complexity-feature-1-preposition--wh-complement-clause-prep__wh) (W8)        
- structural type 2: [non-finite dependent clauses](#structual-type-2-non-finite-dependent-clauses)
    - syntactic function 1: clause constituent adverbial
        - complexity feature 1: [*to*-clause as purpose adverbial](#complexity-feature-1-to-clause-as-purpose-adverbial) (W9)
        - complexity feature 2: [*ing*-clause as adverbial](#complexity-feature-2-ing-clause-as-adverbial) (W9)
        - complexity feature 3: *ed*-clause as adverbial
- structural type 3: [dependent phrases](#structual-type-3-dependent-phrases-non-clausal)


## Quick examples overview

| Examples                                                    | Structural type | Syntactic function        | Tag                          |
|-------------------------------------------------------------|-----------------|---------------------------|--------------------------    |
| *She finished her work <ins>before the deadline arrived</ins>.*  | Finite          | Adverbial               | [`finite_advl_cls`](#syntactic-function-1-clause-constituent-adverbial)          |
| *<ins>That the team won the championship</ins> was unexpected.* | Finite          | Verb complement          | [`V_that_comp`](#complexity-feature-1-verb--that-complement-clause-v_that_comp-v_that_0)               |
| *I wonder <ins>what that could be about</ins>.*                      | Finite          | Verb complement          | [`verb_+_wh`](#complexity-feature-2-verb--wh-complement-clause-verb__wh)          |
| *The idea <ins>which needs be implemented</ins> involves several steps.*  | Finite      | NP complement           | [`finite_rel`](#complexity-feature-1-noun--finite-relative-clause-finite_rel)         |
| *The conclusion <ins>that global temperatures are rising</ins> is alarming.* | Finite      | NP complement           | [`N_that_comp`](#complexity-feature-1-noun--that-complement-clause-n_that_comp)       |
| *We’re happy <ins>that the hunger strike has ended</ins>.*       | Finite          | Adjective complement     | [`adj_that_comp`](#complexity-feature-1-adjective--that-complement-clause-adj_that_comp)            |
| *It's horrible <ins>that he put up with Claire’s nagging</ins>.* | Finite          | Adjective complement     | [`xtrapos+jj+that+compcls`](#complexity-feature-2-extraposed-adjective--that-complement-clause-xtraposjjthatcompcls)  |
| *She is interested in <ins>what you believe</ins>.*              | Finite          | PP complement            | [`prep_+_wh`](#complexity-feature-1-preposition--wh-complement-clause-prep__wh)                |
| *<ins>To verify this hypothesis</ins>, sections of fixed cells were examined.* | Non-finite    | Adverbial                | [`to_advl_cls`](#complexity-feature-1-to-clause-as-purpose-adverbial)              |
| *<ins>Running along the beach</ins>, she found a rare shell.*             | Non-finite      | Adverbial                | [`ing_advl_cls`](#complexity-feature-2-ing-clause-as-adverbial)             |


## Notes

- [passive] We tagged on the **passive**, not on the *be*-verb.
    - *they knew <ins>what they were going to be **asked**.</ins>* (verb-*wh*-complement)
- [coordination] We tagged on the first main verb, not on the following verbs.
    - *a truckdriver <ins>who just **slammed** and kicked at everything</ins>* (noun-finite relative clause)


## Documentation

### Structual type 1: finite dependent clauses
A **finite** dependent clause includes a verb phrase that is characterized by a specific tense or modality (Biber et al., 2007, p. 193).

#### Syntactic function 1: clause constituent adverbial

*description to be added soon*

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
    -  A finite relative clause follows the head noun phrase, and are always missing a constituent (corresponds in meaning to the _head noun_)
    -  _Relativizers_ are one of:
        -  **Relative pronoun:** which, who, whom, whose, that
        -  **Relative adverb:** where, when, why
        -  **Zero relativizer:** relativizer is _ommited_
    - Nominal postmodifiers are different from NP complement clauses (p. 644)
        - e.g *Peter reached out for the well-thumbed report <ins>that **lay** behind him on the cupboard top.</ins>* 
2. Tag
    - `finite_rel` is tagged on the **main verb** of the *that*- of *wh*- relative clause (also include the relative clause with deleted relative pronoun).
3. Examples
    -  *The lowest pressure ratio <ins>which will **give** an acceptable performance</ins> is always chosen.* (Biber et al., 2007, p.608)
    -  *There are plenty of existing owners <ins>who **are** already keen to make the move.</ins>* (*Ibid* p.608)
    -  *There was a slight, furtive boy <ins>whom no one **knew**.</ins>* (*Ibid* p.608)
    -  *It was good for the fans, <ins>whose support so far this season has **been** fantastic.</ins>* (*Ibid* p.608)
    -  *Well, that's the only way <ins>that this can be definitively **assessed**.</ins>*
    -  **Zero Relativizer:**
        -  *The next thing <ins>[that] she **knows**</ins>, she's talking to Danny.* (*Ibid* p.609)
        -  *Gwen gave the little frowning smile <ins>[that] she **used** when she was putting something to someone.</ins>* (*Ibid* p.609)
       
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
    - *The conclusion <ins>that global temperatures are **rising** faster than previously estimated</ins> is alarming.*

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
    - Adjectival predicates with extraposed that-clauses mark a stance or attitude towards the proposition in the that-clause.
        - In most cases, this predicate represents the attitude of the speaker/writer, although it is not overtly attributed to that person.
    - Types of controlling adjectival predicates:
        - **Certainty Adjectives** indicate the extent to which the speaker/writer regards the embedded proposition is *probable*:
            - *accepted, apparent, certain, plain, inevitable, etc.*
        - **Affective/Evaluative Adjectives** mark other assessments or attitudes twoards the proposition in the *that*-clause:
            - *(un)acceptable, preferable, sensible, amazing, bad, funny, dreadful, odd, suprising, neat, etc.*
            - Several evaluative adjectives can occur with an extraposed *that*-clause having a hypothetical sense. These constructions are marked by *should* or subjunctive verb forms.
                - e.g: *It is preferable <ins>that the marked cells [should **be**] identical in their behaviour to the unmarked cells.</ins>* (Biber et al., 2007, p. 674)
        - **Necessity or Importance Adjectives** reflect the writer's belief that a proposed course of action is essential or important:
            - *advisable, critical, crucial, essential, fitting, obligatory, vital, etc.*
2. Tag
    - `xtrapos+jj+that+compcls` is tagged on the **main verb** of the *that*-complement clause.
3. Examples
    - *It has been clear for some time <ins>that the demands of the arms control process would increasingly **dominate** military planning.</ins>* (Biber et al., 2007, p. 673)
    - *It is obvious <ins>that direct chilling of the udder **depends** as much on the thermal properties of the floor as on the air temperature.</ins>* (*Ibid* p. 673)
    - *It's horrible <ins>that he **put up** with Claire's nagging.</ins>* (*Ibid* 673)
    - *It is tragic <ins>that so many of his generation **died** as they did.</ins>* (*Ibid* 673)
    - *It is sensible <ins>that the breeding animals [**receive**] the highest protection.</ins>* (*Ibid* 674)
    - *It is important <ins>that it **be** well sealed from air leakage.</ins>* (*Ibid* 674)
    - *It is vital <ins>that leaking water is **avoided**.</ins>* (*Ibid* 674)

#### Syntactic function 6: other phrase constituent_preposition complement
- A preposition complement serves to complete the meaning of ...

##### Complexity feature 1: preposition + *wh*-complement clause (`prep_+_wh`)

1. Descriptions
   -  *wh*-compliment cluases can be compliments of preopositions and objects of prepositional verbs
   -  *wh*-compliments begin with who, what, when, how, where, why, which, etc.
   -  Common prepositions are in, on, at, by, with, about, and through
   -  Prepositional verbs are verbs that when combined with a preposition may take on new meaning.
2. Tag
   - `prep+wh` is tagged on the **main verb** of the *wh*-complement clause.
4. Examples
   -  *She was amazed at <ins>how exhausted she **was**.</ins>* (Biber et al., 2007, p. 684)
   -  *She is interested in <ins>what you **believe**.</ins>*
   -  *We are searching for <ins>whose idea it **was**.</ins>*
   -  *He is investigating under <ins>whose authority the decision was **made**</ins>.*

### Structual type 2: non-finite dependent clauses

- Non-finite dependent clauses do not feature tense and modality markings. They typically omit an explicit subject and subordinator 

- Semantically, they are compact and a lack of explicitness.

- See more in Biber (2007, pp. 198-201)


#### Syntactic function 1: clause constituent adverbial
*to be added soon*

##### Complexity feature 1: *to*-clause as purpose adverbial

1. Descriptions
   - *To*-clauses as purpose adverbials indicate the reason or intention behind the main action of a sentence.
   - They are introduced by *to* or a deleted *to*
       - *Surrey police say the film would help <ins>[to] **identify** participants at the weekend party</ins>*  
3. Tag
   - `to_advl_cls` is tagged on the **main verb** of the *to*-adverbial clause.
4. Examples
   -  *<ins>To **verify** this hypothesis</ins>, sections of fixed cells were examined.*
   -  *We eat <ins>to **survive**</ins>*
   -  *I have brought you all here today <ins>to **tell** you about my evil plan</ins>*
   -  *Reforming is the process whereby straight-run gasoline is cracked <ins>in order to **raise** the octane number.</ins>* (Biber et al., 2007, p. 827)

##### Complexity feature 2: *ing*-clause as adverbial

1. Descriptions
    - An *ing*-clause when used as an adverbial to modify a verb, an adjective, or an entire sentence. This is often employed to add information about the time, manner, reason, condition, or circumstance of the action described by the main verb.
    - (Dangling particles): Dangling participles occur when a participial phrase (an *ing*-clause or an ed-clause used adverbially) lacks a clear subject, leading to ambiguity or a mismatch between the intended subject and the grammatical subject of the main clause (p. 829). (HS: should we include this case?)         -  *<ins>**Running** to catch the bus</ins>, the wallet fell out of my pocket.* (The wallet is not running; the implied subject is the person.)

2. Tag
   - `ing_advl_cls` is tagged on the **main verb** of the *ing*-adverbial clause.
3. Examples
   -  *<ins>**Considering** mammals’ level of physical development</ins>, the diversity of this species is astounding.*
   - *<ins>**Running** along the beach</ins>, she found a rare shell.* (time)
   - *<ins>**Feeling** hungry</ins>, he stopped at the nearest restaurant.* (reason)
   - *<ins>**Providing** you finish your homework</ins>, you can watch TV.* (condition)
   - *<ins>**Knowing** the risks involved</ins>, she still decided to go paragliding.* (concession)
   - *<ins>**Speaking** softly</ins>, he conveyed the bad news.*

##### Complexity feature 3: *ed*-clause as adverbial
1. Descriptions
    - An *ed*-clause can be used as an adverbial to modify a verb, an adjective, or an entire sentence. This is often employed to add information about comparisons between, levels of expectation of, or some other modification of the action described by the main verb.
2. Tag
   - `ed_advl_cls` is tagged on the **main verb** of the *ed*-adverbial clause.
3. Examples
   - *<ins>When told by police how badly **injured** his victims were</ins> he said: "Good, I hope they die."*
   - *We measured a seasonal total of 56.99 on precipitation in the two caged rain gauges, <ins>**compared** to 56.78 cm on the open plots.</ins>*
   - *I went on waiting, <ins>**tinged** with doubt</ins>.*
   - *<ins>As **expected**</ins>, the volume of retail sales rose 0.5 per cent in August.*

#### Syntactic function 2: Clause constituent_Verb complement
- verb complement (review: 1-2)
  
##### Complexity features 1: Verb + *to* complement clause
1. Descriptions
    - Infinitive clauses can have a range of syntactic roles which include direct objects (pp. 198-199).
2. Tag
    -  `vb+tocls` is tagged on the **main verb** of the *to* complement clause.
3. Examples
    - *I really want <ins>to **fix** this room up</ins>.*
    - *He upset you very much, and I hate <ins>to **see** that</ins>.* (p. 199)
    - *I believe Mary <ins>to **be** innocent</ins>*. (Haegeman & Guéron, 1998, p.126)
    - *I promised John <ins>to buy a new bicycle</ins>*. (Haegeman & Guéron, 1998, p.35)
      
##### Complexity features 2: Verb + *ing* complement clause
1. Descriptions
   - Similar to the infinitive clauses, *ing* complement clauses can also act as a complement to the main verb.
   - This structure is commonly known as the gerund. Gerunds function as a hybrid category, possessing characteristics of both verbs and nouns (Haegeman & Guéron, 1998, p.481).
2. Tag
    -  `vb+ingcls` is tagged on the **main verb** of the *ing* complement clause.
3. Examples
   - *I like <ins>**watching** the traffic go by</ins>.*
   - *I started <ins>**thinking** about Christmas</ins>.* (p. 200)
   - *It's as if the guy never stops <ins>**thinking** about the issue</ins>.* (p.200)
   - *I enjoy <ins>**running** in the morning</ins>.*
   - *He considers <ins>**moving** to a new city</ins>.*
   - *He avoids <ins>**talking** about his problems</ins>.*
     
#### Syntactic function 3: Noun phrase constituent_NP modifier
- np modifier
  
##### Complexity features 1: Noun + *-ed* (passive) relative clause
1. Descriptions
   - Noun + *ed* passive relative clauses exist to modify the noun phrase to provide additional information about the noun.
   - Introduced by a verb in **past** participle form (e.g *donated*, *created*, *espoused*).
       - Some verbs are irregular, such as see (*seen*), write (*written*), or sing (*sung*).
   - Most frequent in academic prose compared to other registers.
2. Tag
   - `nn+edcls+relcl` is tagged on the **main verb** of the *ed* relative clause.
3. Examples
   - *This is a phrase <ins>**used** in the recruitment industry</ins>.*
   - *Abundant food and available healthcare are among the products <ins>**required** to support a huge and growing population.</ins>* (Biber et al., 2007, p. 604)
   - *The castle meeting between the three men <ins>**produced** the Three Musketeers.</ins>*
   - *The final thing the townspeople heard was the battalion's anthem <ins>**sung** as they marched over the hill.</ins>*
  
##### Complexity features 2: Noun + *-ing* relative clause
1. Descriptions
    - Noun + *ing* relative clauses modify the noun phrase and typically describe an ongoing action or activity related to the modified noun.
    - Introduced by verbs in **present** participle form (e.g *lying*, *watching*, *waiting*)
    - Most frequent in academic prose but moderately common across registers.
2. Tag
   - `nn+ingcls+relcl` is tagged on the **main verb** of the *ing* relative clause.
3. Examples
   - *Elevated levels are treated with a diet <ins>**consisting** of low cholesterol foods.</ins>*
   - *The woman <ins>**standing** in the corner</ins> is my sister.*
   - *After the outer walls fell the soldiers found the nobles <ins>**seeking** shelter in the castle</ins>*
   - *They engaged in research <ins>**hoping** to expand human understanding of the world.</ins>*
  
##### Complexity features 3: Noun + *to* relative clause
1. Descriptions
   - Noun + *to* relative clauses modify the noun phrase and provide infomation as to the direction, destination, intention, or subsequent action.
   - They are introduced by *to*, followed by a verb in infinitive form (e.g *play*, *create*, *observe*).
   - More common in conversation than in writing.
2. Tag
   - `to-rel` is tagged on the **main verb** of the *to* relative clause.
3. Examples
   - *You're the best person <ins>to **ask**.</ins>*
   - *There's just a lot <ins>to **think** about.</ins>* (Biber et al., 2007, p. 607)
   - *She is probably the best player <ins>to **play** college basketball.</ins>*
   - *He showed us the way <ins>to **get** to our house.</ins>* (Biber et al., 2007, p. 604)


### Structual type 3: dependent phrases (non-clausal)
#### Adverb phrase as adverbial
1. Descriptions
   - An adverb phrase as adverbial is when an adverb phrase is used to modify a verb, adjective, or an entire sentence.
   - Adverbial adverb phrases give more information about when, where, how, or under what conditions applied to the component they modify.
   - They cannot exist on their own due to being depedent phrases.
2. Tag
   - `adv_as_advl` is tagged on the **adverb** of the adverb phrase.  **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *They arrived <ins>**before** sunrise</ins>*
   - *I will see you <ins>**later** tonight</ins>.*
   - *I raved about it <ins>**afterwards**</ins>.*
   - *He entered the room <ins>**quietly**</ins>.*

#### Prepositional phrase as adverbial
1. Descriptions
   - A prepositional phrase as adverbial is tagged when a prepositional phrase acts like an adverbial, modifying a verb, adjective, or entire sentence.
   - Adverbial prepositional phrases typically correspond to one of these major groups:
       - Location/Place: conveys distance, direction, or position (*she sat **on the bench***)
       - Time: indicate position in time, duration, frequency, or the temporal relation between two states (*We will leave **in the morning***)
       - Process: describe the way something was done, as comparison between two states, accompaniment/grouping, demonstrate the explicit means through which an action was carried out, the item relevant to the state, or the agent of an action. (*He spoke **with enthusiasm***)
       - Contingency: describe the cause, reason, purpose, concession, condition, and/or result (*She can see you **if you stand there***)
   - They cannot exist on their own due to being depedent phrases.
2. Tag
   - `in+advl` is tagged at the **head** of the prepositional phrase. **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *Alright, we'll talk to you <ins>**in** the morning</ins>.*
   - *She avoids the sun <ins>**by** wearing a hat</ins>.*
   - *He left <ins>**because** of the rain</ins>.*
   - *<ins>**During** the concert,</ins> they remained silent.*

#### Attributive adjectives as noun pre-modifier
1. Descriptions
   - Attributive adjectives are adjectives describing particular attributes of the noun they modify.
   - They are pre-modifiers because they come before the noun they modify.
   - They cannot exist on their own due to being depedent (non-clausal) phrases.
2. Tag
   - `attr+nn+premod` is tagged on the **attributive adjective**. **<---- DO WE WANT MULTIPLE TAGS FOR POTENTIALLY MULTIPLE ADJECTIVES?** see example 3
3. Examples
   - *He struggled to read the <ins>**emotional**</ins> inquiry.* 
   - *She drives a <ins>**fast**</ins> car.*
   - *The <ins>**small**</ins>, <ins>**antique**</ins> <ins>**wooden**</ins> chest held many treasures.*
   - *They bought a <ins>**beautiful**</ins> home.

#### Nouns as noun pre-modifier
1. Descriptions
   - Nouns as noun pre-modifiers (sometimes *noun adjunct*) are nouns that add specific information to the following noun.
   - These nouns often communicate meaning related the purpose, type, ownership, or material among other qualities of nouns they modify.
   - They cannot exist on their own due to being depedent (non-clausal) phrases.
2. Tag
   - `nn+npremod` is tagged on the **pre-modifying noun**. **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *The pilot's license needed to be reviewed by the <ins>**avitation security**</ins> committee.*
   - *He barely passed <ins>**fighter pilot**</ins> training.*
   - *She placed her <ins>**coffee**</ins> cup on the table.*
   - *The city council is considering a new <ins>**traffic regulation**</ins> proposal.*

#### *Of* genitive phrases as noun post-modifier
1. Descriptions
   - *Of* genitive phrases can modify nouns and express relationship between nouns, linked by *of.*
   - The *of* genetive phrase comes after the noun it relates to, therefore being considered a post-modifier.
   - They cannot exist on their own due to being depedent (non-clausal) phrases.
2. Tag
   - `of+gen+post+nmod` is tagged on the **noun** of the *of* genitive phrase. **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *The sound <ins>of **music**</ins> was soothing.*
   - *McKenna wrote about the origins <ins>of human **language**.</ins>*
   - *She is the CEO <ins>of the **company**.</ins>*
   - *A group <ins>of **students**</ins> gathered in the hall.*

#### Other prepositional phrases as noun post-modifier
1. Descriptions
   - Similar to *of* genetive phrases, but relatively rarer in occurence. This tag includes all other prepositional phrases that follow a noun and modify it.
   - Linked by words such as *in*, *which*, *on*, among others that are not *of*.
   - They cannot exist on their own due to being depedent (non-clausal) phrases.
2. Tag
   - `in+post+nmod` is tagged on the **preposition** of the prepositional phrase. **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *The painting <ins>**in** the corner</ins> caught my eye.*
   - *The conference <ins>**on** global warming</ins> was very informative.*
   - *Your cake <ins>**with** chocolate icing</ins> was delicious.*
   - *Children <ins>**under** twelve</ins> get in for free.*

#### Appositive noun phrases as noun post-modifier
1. Descriptions
   - Noun phrases in apposition (appositive) have equivalent status with the preceding (head) noun phrase.
       - The order of the head noun phrase and the appositive could (nomally) be reversed to produce an equal grammatical construction with basically the same meaning.
   - They provide descriptive information about the head noun but are not needed to identify the reference of the head noun.
   - They cannot exist on their own due to being depedent (non-clausal) phrases.
2. Tag
   - `nn+nappos` is tagged on the **noun** of the appositive phrase. **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *The capital city, <ins>**Paris**</ins>, is the heart of France.*
       - *Paris, <ins>the capital **city**</ins>, is the heart of France.* 
   - *The famous inventor <ins>**Thomas** Edison</ins> made numerous advancements in technology.*
       - *Thomas Edison, <ins>the famous **inventor**</ins>, made numerous advancements in technology.*
   - *My brother <ins>**John**</ins> is a painter.*
   - *My friend, <ins>an experienced **hiker**,</ins> has traveled far and wide.*
  
#### Prepositional phrases as adjective complement
1. Descriptions
   - Prepositional phrases can function as adjective complements when they follow an adjective and complete/enhance its meaning.
   - They begin with prepositions, commonly *in*, *about*, *to*, etc.
   - They cannot exist on their own due to being depedent (non-clausal) phrases.
2. Tag
   - `adj_+_prep` is tagged on the **preposition** of the complement prepositional phrase. **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *The solution was obvious <ins>**to** everyone in the room</ins>.*
   - *She was happy <ins>**about** the promotion</ins>.*
   - *He is interested <ins>**in** ancient history</ins>.*
   - *The novel is relevant <ins>**to** current events</ins>.*

#### Adverb phrase as adjective/adverb modifier
1. Descriptions
   - An adverb phrase modifies an adjective or another adverb when it provides more information about the adjective or adverb.
       - Commonly modifying the degree, intensity, or manner of the adjective/adverb.
   - They can often be a single word (e.g *quite* unsure, *extremely* unhelpful) but may extend to more than one (e.g *a little* dissappointed, *not entirely* sure).
       - Adverbs can be observed commonly ending with *-ly*.
   - They cannot exist on their own (independently) due to being depedent (non-clausal) phrases.
2. Tag
   - `adv_as_modifier` is tagged on the **adverb** of modifying adverb phrase. **<---- NOT SURE WHAT IS DESIRED HERE**
3. Examples
   - *That cat was <ins>**suprisingly**</ins> fat.*
   - *We will see those impacts <ins>**fairly**</ins> quickly.*
   - *Depite the captain's best efforts, the team was <ins>not **entirely**</ins> sure about the plan.*
   - *The boy was <ins>**fairly**</ins> certain that it would rain due to the heavy smell in the air.*
-------

#### Noun + *to* complement clause
1. Descriptions
   - Noun + *to* compliment clauses modify the noun and provide a purpose or potential action related to the noun.
   - Noun + *to* complement clauses are non-finite, and have missing subjects that can be reconstructed from the context of the sentence.
   - They do not have gaps corresponding to the heads of the sentences.
2. Tag
   - `nn+tocls+ncomp` is tagged on the **main verb** of the *to* compliment clause.
3. Examples
   - *You've been given permission <ins>to **wear** them.</ins>* (Biber et al., 2007, p. 645)
   - *Legal peers renewed their attack on the Government's plans <ins>to **shake** up the legal profession</ins> yesterday.* (Biber et al., 2007, p. 645)
   - *She seized every opportunity <ins> to **learn** new skills</ins> during the workshop.*
   - *His decision <ins>to **move** to New York</ins> was influenced by the promise of better job prospects.*

#### Adjective + *to* complement clause
1. Descriptions
   - Adjective + *to* complement clauses usually introduce an infinitive verb following the *to*
   - Adjective + *to* complement clauses provide more information to the state or quality described by the adjective, and can specify potential actions or conditions related to the subject.
2. Tag
   - `jj+tocls+jcomp` is tagged on the **main verb** of the *to* compliment clause.
3. Examples
   - *Millar was obstinately determined <ins>to **change** the content of education.</ins>* (Biber et al., 2007, p. 716)
   - *They were excited <ins>to **explore** the new city</ins>, having heard so much about its vibrant culture.*
   - *After recovering from her injury, she was able <ins>to **participate** in the marathon</ins>, much to her relief.*

#### Extraposed adjective + *to* complement clause
1. Descriptions
   - Extraposed adjective + *to* complement clauses semantically function as the subject.
   - The true subject is often replaced by *it.*
2. Tag
   - `xtrapos+jj+tocls+jcomp` is tagged on the **main verb** of the extraposed *to* compliment clause.
3. Examples
   - *It was difficult <ins>to **appreciate him</ins> when we thought we had more time.*
   - *It is important <ins>to **understand** other people's feelings</ins> in a team enviornment.*
   - *It was necessary <ins> to **adjust** our plans</ins> due to the unexpected weather conditions.*
   - *They were excited <ins>to **get** the chance</ins> to play in the tournament.*
  
#### Preposition + *-ing* complement clause
1. Descriptions
   - Preposition + *-ing* complement clauses are constructed from a preposition and a verb in its *-ing* form.
   - It is used to provide additional information about the context or manner in which the action of the main verb occurs, or to describe relationships in time, cause, method, or condition
2. Tag
   - `ingcls+incomp` is tagged on the **main verb** of the *-ing* compliment clause.
3. Examples
   - *After <ins>**finishing** his homework</ins>, John went out to play.*
   - *Despite <ins>**feeling** unwell</ins>, she attended the meeting.*
   - *Without <ins>**realizing** it</ins>, she offended her colleague with a casual remark.*
   - *Nearly <ins>**crashing** into each other</ins>, the two pedestrians both ran into others.*

----

### References
- Biber, D., Johansson, S., Leech, G., Conrad, S., & Finegan, E. (2007). *Longman Grammar of Spoken and Written English (6th ed.).* Longman.

- Haegeman, L., & Guéron, J. (1998). *English grammar: A generative perspective (Vol. 12).* John Wiley & Sons.
