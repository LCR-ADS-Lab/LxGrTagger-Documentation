---
title: Discussions
nav_order: 5
---

# Discussions
{: .no_toc }

1. TOC
{:toc}

## Semi-modals 

The following semi-modals were pre-processed before parsing and tagging sentence structures: *have to, had to, got to, have/had got to, gotta, ought to, BE supposed to, BE going to, gonna, BE about to,* and *used to.*

**Notes:**
- *BE* includes all its inflected forms for person and tense.
- *used to* is treated as a semi-modal only when it is **not** preceded by *BE*.

## Passive

We tagged the **passive** construction, not the *be*-verb itself.

- *They knew <ins>what they were going to be **asked**.</ins>* (verb-*wh*-complement)

## Coordination

### Verb

We tagged the first main verb, not the subsequent verbs.

- *A truck driver <ins>who just **slammed** and kicked at everything</ins>* (noun-finite relative clause)
- *He suggested <ins>that they should **stop** and go</ins>* (verb *that*-complement clause) 

### Clause

We tagged every verb in each clause.

- *He said <ins>he was **tired**</ins></ins> but <ins>he **needed** a break</ins>* (coordinated *that*-complement clauses)

## Multi-words

We defined several lists of fixed multi‐word sequences that are used during the processing of linking adverbs (pp. 558-559; 875-879), prepositions (p. 75), subordinators (pp.842-843). 

### Multi-word linking adverbs

```markdown
for one thing, in other words, for another, for another thing, in the first place, in the second place, first of all, to begin with, in addition, in sum, to conclude, by the same token, all in all, in conclusion, to summarize, which is to say, for example, for instance, on the other hand, in contrast, on the contrary, by comparison, in any case, at any rate, in spite of, after all, by the way
```

### Two-word prepositions 

```markdown
as for, but for, except for, save for, as from, as of, out of, depending on, according to, as to, on to, up to, along with, apart from, aside from, away from, ahead of, inside of, instead of, irrespective of, outside of, regardless of, close to, contrary to, next to, opposite to, owing to, preliminary to, preparatory to, previous to, prior to, relative to, subsequent to, together with, back to, sort of, kind of, devoid of, exclusive of, void of, because of, due to, exclusive of, owing to, thanks to, such as, upwards of
```

### Three-word prepositions

```markdown
as far as, as opposed to, as distinct from, in exchange for, in return for, by means of, by virtue of, by way of, for lack of, for want of, in aid of, in back of, in case of, in charge of, in consequence of, in favour of, in front of, in lieu of, in light of, in need of, in place of, in respect of, in search of, in spite of, in terms of, in view of, on account of, on behalf of, on grounds of, on top of, by reference to, in addition to, in contrast to, in reference to, in regard to, in relation to, with regard to, with reference to, with respect to, at variance with, in accordance with, in comparison with, in compliance with, in conformity with, in contact with, in line with, as a result of, at the expense of, for the sake of, in the case of, in the event of, in the light of, on the grounds of, on the ground of, on the part of, with the exception of, at the back of, in the middle of
```

### Multi-word subordinators

```markdown
as if, as though, so that, in that
```
