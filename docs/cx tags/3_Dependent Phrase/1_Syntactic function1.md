---
title: Adverbial
parent: Dependent Phrase
nav_order: 1
---


# Adverbial

## adverb phrase

1. Descriptions
   - An adverb phrase is adverbial when an adverb phrase is used to modify a verb or an entire sentence.
   - Adverbial adverb phrases give more information about when, where, how, what degree, or under what conditions applied to the component they modify.
2. Tag
   - `rb+advl` is tagged on the **adverb** of the adverb phrase.
3. Examples
   - *They arrived <ins>**before** sunrise</ins>*
   - *I will see you <ins>**later** tonight</ins>.*
   - *I raved about it <ins>**afterwards**</ins>.*
   - *He entered the room <ins>**quietly**</ins>.*
4. Discussions
   - We do not tag linking adverbs such as:
   ```markdown
   first, second, secondly, thirdly, lastly, altogether, overall, namely, ie, therefore, thus, however, alternatively, incidentally, now, next, further, similarly, also, likewise, moreover, i.e., e.g., consequently, so, then, anyway, yet, conversely, instead, anyhow, besides, nevertheless, still
   ```
   - Check out the list of the multi-word linking adverbs [here](https://lcr-ads-lab.github.io/LxGrTagger-Documentation/docs/Discussions/#multi-words).
   - Interpretation of some linking adverbs is based on the context in which they appear. For example,
      - *<ins>**Now**</ins>, let's examine the results of the experiment.* (The adverb "now" serves as an introductory adverb to transition into the analysis, so it is not tagged.)
      - *I need the report <ins>**now**.</ins>* (The adverb "now" is used as a temporal indicator to denote immediacy, rather than serving as a linking adverb, so it is tagged.)
---

## preposition phrase

1. Descriptions
   - A prepositional phrase as adverbial is tagged when a prepositional phrase acts like an adverbial, modifying a verb or entire sentence.
   - Adverbial prepositional phrases typically correspond to one of these major groups:
       - Location/Place: conveys distance, direction, or position (*she sat **on the bench***)
       - Time: indicate position in time, duration, frequency, or the temporal relation between two states (*We will leave **in the morning***)
       - Process: describe the way something was done, as comparison between two states, accompaniment/grouping, demonstrate the explicit means through which an action was carried out, the item relevant to the state, or the agent of an action. (*He spoke **with enthusiasm***)
       - Contingency: describe the cause, reason, purpose, concession, condition, and/or result (*She could not see you **under the spotlight***)
   - They cannot exist on their own due to being depedent phrases.
2. Tag
   - `in+advl` is tagged on the **preposotion** of the prepositional phrase.
3. Examples
   - *Alright, we'll talk to you <ins>**in** the morning</ins>.*
   - *He left <ins>**because** of the rain</ins>.* (Q. Do we tag *because*? or *of*?)
   - *<ins>**During** the concert,</ins> they remained silent.*
4. Discussions
   - We are currently not tagging prepositional verbs, so the prepositions in such cases should be tagged.
      - *...we're looking <ins>**at** the rate of return versus what?</ins>*
   - Comparative constructions can be complex in English grammar, often involving combinations with prepositions. We currently tag these as prepositions.
      - *She is as tall <ins>**as** her brother</ins>.*
      - *He is taller <ins>**than** his friend</ins>.*
   - Check out the list of the multi-word linking prepositions [here](https://lcr-ads-lab.github.io/LxGrTagger-Documentation/docs/Discussions/#multi-words).
