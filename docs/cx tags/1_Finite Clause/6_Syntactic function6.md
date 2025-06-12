---
title: Verb complement
parent: Finite Dependent Clause
nav_order: 6
---

# Verb complement

## verb + *that*-complement

1. Descriptions
    - Verbs controlling *that*-clauses are categorized into three domains (p. 661):
        - Mental verbs: Pertaining to cognition and often including emotive/affective content (e.g., *hope*, *believe*, *feel*, *find*, *guess*, *know*, *see*, *think*, *assume*, *conclude*).
        - Speech act verbs: Specifically denote speech activities (e.g., *say*, *admit*, *agree*, *announce*, *argue*, *bet*, *insist*).
        - Other communication verbs: May not directly involve speech (e.g., *show*, *suggest*, *ensure*, *indicate*, *prove*).
2. Tag
    - `thatcls+vcomp` (including a ZERO complementizer) is tagged to the **main verb** within the *that*-complement clause.
3. Examples
    - *I didn't agree <ins>that he should be **compelled** to do singing.</ins>* (p. 661)
    - *I suggested <ins>that she **sit** down on the chair and wait.</ins>* (p. 662)
    - *I would hope <ins>that we can **have** more control over them.</ins>*
    - *I propose <ins>that Mary should be **invited**.</ins>* (Haegeman & Guéron, 1998, p. 441)
4. Discussions/Open Questions
    - *It seems <ins>that he brought that cup to his house</ins>.*
    - **Q:** How do we tag extraposed verbs?
    - **Q:** Should we include *if/whether-*complement clause here? or into the next category?

---

## *BE*verb + *that*-complement

1. Descriptions
    - This feature involves a copular verb (*be*) followed by a *that*-complement clause, typically introduced by *that* but sometimes with a zero complementizer. 
2. Tag
    - `thatcls+BEcomp` is tagged to the **main verb** within the *that*-complement clause.
3. Examples
    - *The finding is <ins>that fear **improved** the partial memory.</ins>*
    - *The point is <ins>that we need to **act** quickly</ins>.*

---

## extraposed verb + *that*-complement clause 

1. Descriptions
    - The *that*-complement clause is often extraposed , and a dummy subject (*it*) occupies the subject position. The matrix verb is typically cognitive or communicative (e.g., *seem, appear, make clear*). Both active and passive voice constructions are common: 
        - Active voice: *It seems that..., It appears that...*
        - Passive voice: *It is said that..., It was found that..., It has been shown that...*
2. Tag
    - `xtrapos+thatcls+vcomp` is tagged to the **main verb** within the *that*-complement clause.
3. Examples
    - *It seems <ins>that he **lied** about the whole thing</ins>.*
    - *It appears <ins>that she **was** right all along</ins>.*
    - *It is said <ins>that the company will **expand** next year</ins>.*
    - *It was found <ins>that participants **performed** better under pressure</ins>.*
    - *It has been shown <ins>that stress **affects** memory</ins>.*

---

## verb + *wh*-complement

1. Descriptions
    - *wh*-clauses can be either dependent (1) interrogative clauses or (2) nominal relative clauses (p. 683).
    - Common *wh*-words: *what*, *who*, *where*, *when*, *why*, *how*, and *whether*
    - Types:
        - Interrogative clauses: Used with verbs like *ask* and *wonder* to present indirect questions.
            - e.g., *I wonder <ins>what that could **be** about</ins>.*
        - Nominal relative clauses: Can be paraphrased by a general head noun modified by the *wh*-clause (e.g., *<ins>Whoever **solves** this problem</ins> will be successful.* → *The person who solves this problem will be successful.*)
            - e.g., *<ins>What **baffles** me</ins> is how few of them can spell.* 
2. Tag
    -  `whcls+vcomp` is tagged on the **main verb** of the *wh*-complement clause.
3. Examples
    - *I don't know <ins>how they **do** it.</ins>*
    - *She showed me <ins>where we should **plant** the tree.</ins>*
    - *He described <ins>what he **saw** at the event.</ins>*
    - *No one knows <ins>how long the journey will **take**.</ins>*
    - *"What I don't understand," she said, "is <ins>why they don't **let** me know anything.</ins>"* (p. 193)
    - *that's <ins>how I **did** it.</ins>* (dataset)

---

## *BE*verb + *wh*-complement

1. Descriptions
    - This feature involves a copular verb (*be*) followed by a *wh*-complement clause, where the clause serves as the complement to a subject noun phrase.
2. Tag
    - `whcls+BEcomp` is tagged to the **main verb** within the *wh*-complement clause.
3. Examples
    - *The question is <ins>who **called** last night</ins>.*
    - *The issue was <ins>where they **went** afterward</ins>.*
    - *The mystery is <ins>how he **escaped** unnoticed</ins>.*

---

## extraposed verb + *wh*-complement clause 

1. Descriptions
    - The *wh*-complement clause can be extraposed to the end of the sentence, and a dummy subject (*it*) occupies the initial subject position.
2. Tag
    - `xtrapos+whcls+vcomp` is tagged to the **main verb** within the *wh*-complement clause.
3. Examples
    - *It depends on <ins>how they **respond**</ins>.*
    - *It is unclear <ins>who **started** the fire</ins>.*
    - *It doesn’t matter <ins>what she **thinks**</ins>.*
    - *It remains to be seen <ins>how the public will **react**</ins>.*

---

**Complements**

Complements are often required to form a grammatically complete and meaningful sentence. Consider the following examples, where grammatically incorrect sentences are indicated with <sup>*</sup> (Haegeman & Guéron, 1998, pp. 21-22):

- a. *He abandoned the project.*
- b. *<sup>*</sup>He abandoned.*
- c. *<sup>*</sup>He abandoned after the project.*
- d. *He abandoned the book.*
- e. *He abandoned the project, then the book.*

These examples show that the verb *abandon* must be followed by a noun phrase (e.g., *the project*). If the verb is not accompanied by a noun phrase, the sentence is incomplete and therefore ungrammatical (as seen in examples b and c).

**Verb complement clauses**

Verb complement clauses are dependent clauses that serve to complete the meaning of a verb in a main clause (e.g., *I think <ins>that this doc looks good</ins>*; *that*-clause functions a complement to the verb *think*). These clauses are also called **nominal clauses** because they frequently occupy a noun phrase slot in the sentence, acting as subjects, objects, or predicatives. Depending on the controlling predicate, they can be found in both pre-predicate (subject) and post-predicate (e.g., direct object) positions (For more information, see Chapter 9).

However, complement clauses can also complete the meaning of an adjectival predicate rather than a verb in the main clause (e.g., *I've gotta be careful <ins>that I don't sound too formal</ins>*). Here, the term *predicate* refers to both lexical verbs and copula+adjective combinations capable of governing a complement clause. This aspect will be further explored in the section on adjective complement.

There are four types of **verb complement clauses**: (1) *that*-clause, (2) *wh*-clause, (3) *to*-infinitive clause, and (4) *ing*-clause. In this section, (1) and (2) are discussed because they are finite clauses, while (3) and (4) will be discussed in the section on non-finite clause verb complements.

