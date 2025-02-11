---
sort: 1
---

# Discussions
This section includes some of the pre-processing rules we discussed based on the functionality of the tagger.

## Semi-modals 

The following semi-modals were pre-processed before parsing and tagging sentence structures: *have to, had to, got to, have/had got to, gotta, ought to, BE supposed to, BE going to, gonna, BE about to,* and *used to.*

**Notes:**
1. BE includes all its inflected forms for person and tense.
2. *used to* is treated as a semi-modal only when it is **not** preceded by BE.

## Passive

We tagged the **passive** construction, not the *be*-verb itself.

- *They knew <ins>what they were going to be **asked**.</ins>* (verb-*wh*-complement)

## Coordination

We tagged the first main verb, not the subsequent verbs.

- *A truck driver <ins>who just **slammed** and kicked at everything</ins>* (noun-finite relative clause)

## Multi-words prepositions and subordinators

We defined several lists of fixed multi‐word sequences that are used during the processing of prepositions and subordinators. 

### Two-word multi-words prepositions
- *as for, but for, except for, save for, as from, as of, out of, depending on, according to, as to, on to, up to, along with, apart from, aside from, away from, ahead of, inside of, instead of, irrespective of, outside of, regardless of, close to, contrary to, next to, opposite to, owing to, preliminary to, preparatory to, previous to, prior to, relative to, subsequent to, together with, back to, sort of, kind of, devoid of, exclusive of, void of, because of, due to, exclusive of, owing to, thanks to, such as, upwards of*

### Three-word multi-words prepositions
- *as far as, as opposed to, as distinct from, in exchange for, in return for, by means of, by virtue of, by way of, for lack of, for want of, in aid of, in back of, in case of, in charge of, in consequence of, in favour of, in front of, in lieu of, in light of, in need of, in place of, in respect of, in search of, in spite of, in terms of, in view of, on account of, on behalf of, on grounds of, on top of, by reference to, in addition to, in contrast to, in reference to, in regard to, in relation to, with regard to, with reference to, with respect to, at variance with, in accordance with, in comparison with, in compliance with, in conformity with, in contact with, in line with, as a result of, at the expense of, for the sake of, in the case of, in the event of, in the light of, on the grounds of, on the ground of, on the part of, with the exception of, at the back of, in the middle of*

### Two-word multi-words subordinators
- *as if, as though, so that, in that*