---
title: Multiword units and special cases
nav_order: 5
---

# Multiword units and special cases
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

### Verb phrase

In coordinated verb phrases, we tagged the first main verb, not the subsequent verbs.

- *A truck driver <ins>who just **slammed** and kicked at everything</ins>* (noun-finite relative clause)
- *He suggested <ins>that they should **stop** and go</ins>* (verb *that*-complement clause) 

### Clause

In coordinated clauses, we tagged each verb that included an overt subject.

- *He said <ins>he was **tired**</ins> but <ins>he **needed** a break</ins>* (coordinated *that*-complement clauses)

## Multi-words

We defined several lists of fixed multi‐word sequences that are used during the processing of linking adverbs (pp. 558-559; 875-879), prepositions (p. 75), subordinators (pp. 842-843). In each case, any relevant tags are assigned to the last word of the multi-word sequence.

### Multi-word linking adverbs

```markdown
for one thing, in other words, for another, for another thing, in the first place, in the second place, first of all, to begin with, in addition, in sum, to conclude, by the same token, all in all, in conclusion, to summarize, which is to say, for example, for instance, on the other hand, in contrast, on the contrary, by comparison, in any case, at any rate, in spite of, after all, by the way
```

### Two-word prepositions 

```markdown
as for, but for, except for, save for, as from, as of, out of, depending on, according to, as to, on to, up to, along with, apart from, aside from, away from, ahead of, inside of, instead of, irrespective of, outside of, regardless of, close to, contrary to, next to, opposite to, preliminary to, preparatory to, previous to, prior to, relative to, subsequent to, together with, back to, sort of, kind of, devoid of, void of, because of, due to, exclusive of, owing to, thanks to, such as, upwards of
```

### Three-word prepositions

```markdown
as far as, as opposed to, as distinct from, in exchange for, in return for, by means of, by virtue of, by way of, for lack of, for want of, in aid of, in back of, in case of, in charge of, in consequence of, in favour of, in front of, in lieu of, in light of, in need of, in place of, in respect of, in search of, in spite of, in terms of, in view of, on account of, on behalf of, on grounds of, on top of, by reference to, in addition to, in contrast to, in reference to, in regard to, in relation to, with regard to, with reference to, with respect to, at variance with, in accordance with, in comparison with, in compliance with, in conformity with, in contact with, in line with, as a result of, at the expense of, for the sake of, in the case of, in the event of, in the light of, on the grounds of, on the ground of, on the part of, with the exception of, at the back of, in the middle of
```

### Multi-word subordinators

```markdown
as if, as though, so that, in that
```

## Phrasal and Prepositional Verbs

### Phrasal verbs

Phrasal verbs are treated as a single verb form, but unlike other multi-word units, any associated tag is annotated on the verb (not the particle). Phrasal verb designations are based on annotations in the OntoNotes5 database (Weischedel et al., 2014), which consists of ~2.5 million tokens (for the English subset).


### Prepositional verbs


Prepositional verbs are treated like any other verb + preposition combination. Note that in some cases, the same form can be treated as a phrasal verb or a prepositional verb, depending on the grammatical context. 

Consider:
It **came out** that he had committed a crime. (phrasal verb)

I'm **coming** *out of* my cave and I am doing just fine. (prepositional verb with a multi-word preposition)

Below is a long table of phrasal verbs found in the 4.5 million Slate subcorpus of the OANC that occur at least five times. The table includes each form's frequency as a phrasal verb and as a prepositional verb (where applicable).

| verbBigram | PhrasalVerbFreq | PrepositionalVerbFreq |
| ---------- | --------------- | --------------------- |
| point out | 846 | 0 | 
| turn out | 492 | 2 | 
| go on | 491 | 123 | 
| end up | 321 | 0 | 
| find out | 294 | 1 | 
| come up | 260 | 1 | 
| pick up | 247 | 0 | 
| grow up | 218 | 1 | 
| come out | 215 | 87 | 
| figure out | 211 | 0 | 
| make up | 207 | 0 | 
| give up | 192 | 0 | 
| set up | 181 | 0 | 
| show up | 171 | 0 | 
| check out | 134 | 0 | 
| take up | 133 | 0 | 
| take over | 133 | 2 | 
| take on | 131 | 12 | 
| get away | 97 | 0 | 
| sign up | 93 | 0 | 
| sum up | 89 | 0 | 
| turn up | 89 | 0 | 
| work out | 87 | 3 | 
| carry out | 79 | 0 | 
| rule out | 78 | 2 | 
| stand up | 77 | 0 | 
| wind up | 76 | 0 | 
| fill in | 76 | 15 | 
| wake up | 76 | 0 | 
| take off | 71 | 4 | 
| shut down | 70 | 0 | 
| set off | 70 | 1 | 
| lay out | 69 | 0 | 
| come in | 69 | 113 | 
| hold up | 69 | 0 | 
| keep up | 69 | 0 | 
| catch up | 67 | 1 | 
| add up | 66 | 0 | 
| give away | 65 | 1 | 
| cut off | 64 | 0 | 
| bring in | 60 | 3 | 
| begin with | 59 | 135 | 
| turn down | 58 | 0 | 
| pay off | 58 | 0 | 
| serve up | 58 | 0 | 
| put up | 58 | 0 | 
| break down | 58 | 0 | 
| put out | 58 | 5 | 
| throw out | 58 | 11 | 
| blow up | 57 | 0 | 
| sell out | 57 | 2 | 
| open up | 57 | 0 | 
| break up | 57 | 0 | 
| single out | 56 | 0 | 
| run out | 55 | 24 | 
| leave out | 55 | 7 | 
| come across | 55 | 18 | 
| put on | 55 | 57 | 
| weigh in | 54 | 2 | 
| clean up | 53 | 0 | 
| come off | 53 | 12 | 
| take in | 52 | 23 | 
| set out | 51 | 0 | 
| pass along | 51 | 1 | 
| cover up | 51 | 0 | 
| turn over | 50 | 0 | 
| come along | 49 | 0 | 
| bring out | 49 | 0 | 
| go out | 48 | 42 | 
| hang out | 47 | 0 | 
| bring about | 47 | 2 | 
| pass on | 47 | 7 | 
| take out | 46 | 11 | 
| bring up | 45 | 0 | 
| crack down | 45 | 0 | 
| hold out | 45 | 1 | 
| follow up | 44 | 0 | 
| wipe out | 44 | 0 | 
| turn on | 44 | 44 | 
| start out | 42 | 0 | 
| hand out | 42 | 0 | 
| bring down | 41 | 0 | 
| line up | 41 | 0 | 
| shut up | 41 | 0 | 
| get out | 40 | 78 | 
| look up | 40 | 0 | 
| spell out | 40 | 0 | 
| shoot down | 39 | 0 | 
| come down | 39 | 4 | 
| turn in | 39 | 6 | 
| come on | 38 | 31 | 
| wrap up | 38 | 0 | 
| get up | 37 | 4 | 
| live up | 37 | 7 | 
| pop up | 37 | 0 | 
| break out | 37 | 6 | 
| hand over | 36 | 0 | 
| sit down | 36 | 0 | 
| write off | 36 | 1 | 
| play out | 36 | 1 | 
| get off | 35 | 36 | 
| cash in | 33 | 1 | 
| speak out | 33 | 0 | 
| back down | 33 | 0 | 
| go up | 33 | 5 | 
| fill out | 33 | 0 | 
| screw up | 32 | 0 | 
| pull out | 32 | 14 | 
| work up | 32 | 1 | 
| dig up | 32 | 0 | 
| turn off | 32 | 0 | 
| step down | 32 | 0 | 
| print out | 32 | 0 | 
| bail out | 31 | 0 | 
| stand out | 31 | 0 | 
| track down | 31 | 0 | 
| pull off | 31 | 5 | 
| show off | 31 | 0 | 
| shore up | 30 | 0 | 
| carry on | 30 | 7 | 
| make out | 30 | 5 | 
| send out | 29 | 0 | 
| put in | 29 | 39 | 
| give in | 29 | 13 | 
| sell off | 29 | 0 | 
| back up | 29 | 0 | 
| suck up | 29 | 0 | 
| strike down | 29 | 0 | 
| beat up | 29 | 0 | 
| move on | 28 | 9 | 
| conjure up | 28 | 0 | 
| take away | 28 | 0 | 
| get in | 28 | 76 | 
| shell out | 28 | 0 | 
| kick off | 27 | 1 | 
| lay off | 27 | 0 | 
| throw in | 27 | 3 | 
| log on | 27 | 0 | 
| write in | 27 | 299 | 
| sort out | 27 | 0 | 
| rip off | 26 | 3 | 
| dress up | 26 | 0 | 
| back off | 26 | 5 | 
| put off | 26 | 0 | 
| keep on | 26 | 6 | 
| get along | 26 | 0 | 
| go down | 26 | 13 | 
| cut down | 26 | 0 | 
| go along | 26 | 1 | 
| catch on | 26 | 11 | 
| cry out | 25 | 0 | 
| step up | 25 | 0 | 
| sign on | 25 | 5 | 
| reach out | 25 | 1 | 
| build up | 25 | 0 | 
| stave off | 25 | 0 | 
| hold back | 24 | 0 | 
| hold on | 24 | 11 | 
| act out | 24 | 3 | 
| offer up | 24 | 0 | 
| put down | 24 | 0 | 
| trot out | 24 | 0 | 
| hand down | 24 | 0 | 
| call in | 24 | 6 | 
| slow down | 24 | 0 | 
| pass up | 23 | 0 | 
| buy up | 23 | 0 | 
| boil down | 23 | 0 | 
| play up | 23 | 0 | 
| round up | 23 | 0 | 
| light up | 22 | 0 | 
| pick out | 22 | 2 | 
| dole out | 22 | 0 | 
| get on | 22 | 53 | 
| send in | 22 | 5 | 
| speed up | 22 | 0 | 
| hold off | 22 | 0 | 
| rein in | 21 | 0 | 
| cut back | 21 | 0 | 
| lock up | 21 | 0 | 
| throw up | 21 | 0 | 
| stir up | 21 | 0 | 
| fend off | 21 | 0 | 
| stake out | 20 | 0 | 
| usher in | 20 | 0 | 
| give out | 20 | 0 | 
| spring up | 20 | 0 | 
| pay out | 20 | 2 | 
| kill off | 20 | 0 | 
| kick in | 20 | 1 | 
| call off | 19 | 2 | 
| crop up | 19 | 0 | 
| shake up | 19 | 0 | 
| hook up | 19 | 0 | 
| bring on | 19 | 1 | 
| speak up | 19 | 0 | 
| swear in | 19 | 0 | 
| scale back | 19 | 0 | 
| go off | 19 | 17 | 
| hang up | 18 | 0 | 
| win over | 18 | 7 | 
| tie up | 18 | 0 | 
| lash out | 18 | 0 | 
| start off | 18 | 0 | 
| pass off | 18 | 0 | 
| cough up | 18 | 0 | 
| prop up | 18 | 0 | 
| dry up | 18 | 0 | 
| gloss over | 17 | 3 | 
| hang on | 17 | 15 | 
| come through | 17 | 8 | 
| churn out | 17 | 0 | 
| auction off | 17 | 0 | 
| team up | 17 | 0 | 
| write up | 17 | 0 | 
| cave in | 16 | 0 | 
| brush off | 16 | 0 | 
| call up | 16 | 0 | 
| rack up | 16 | 0 | 
| feed up | 16 | 0 | 
| run up | 16 | 3 | 
| cut out | 16 | 1 | 
| seek out | 16 | 0 | 
| drop out | 15 | 34 | 
| use up | 15 | 0 | 
| come about | 15 | 0 | 
| spin off | 15 | 0 | 
| watch out | 15 | 0 | 
| fit in | 15 | 3 | 
| stamp out | 15 | 1 | 
| go through | 15 | 102 | 
| flesh out | 15 | 0 | 
| push through | 15 | 6 | 
| lay down | 15 | 0 | 
| roll out | 15 | 1 | 
| blow away | 14 | 0 | 
| tick off | 14 | 0 | 
| pass over | 14 | 4 | 
| move in | 14 | 30 | 
| rake in | 14 | 0 | 
| pin down | 14 | 0 | 
| cook up | 14 | 0 | 
| help out | 14 | 1 | 
| point up | 14 | 0 | 
| whip up | 14 | 0 | 
| give over | 14 | 1 | 
| check in | 14 | 0 | 
| clear up | 14 | 0 | 
| live out | 14 | 1 | 
| screen out | 14 | 0 | 
| sign off | 14 | 0 | 
| wear out | 14 | 0 | 
| hunt down | 14 | 0 | 
| ratchet up | 14 | 0 | 
| drown out | 13 | 0 | 
| gear up | 13 | 0 | 
| pony up | 13 | 0 | 
| rise up | 13 | 0 | 
| look out | 13 | 6 | 
| opt out | 13 | 4 | 
| dream up | 13 | 0 | 
| head up | 13 | 0 | 
| mix up | 13 | 0 | 
| miss out | 13 | 0 | 
| fill up | 13 | 0 | 
| close down | 13 | 0 | 
| tune in | 13 | 1 | 
| roll over | 13 | 1 | 
| tear down | 13 | 1 | 
| get by | 13 | 3 | 
| drive out | 13 | 4 | 
| draw up | 13 | 0 | 
| chalk up | 13 | 0 | 
| break off | 13 | 0 | 
| warm up | 13 | 0 | 
| hold forth | 13 | 0 | 
| drive up | 13 | 0 | 
| pass out | 12 | 1 | 
| lock in | 12 | 29 | 
| mess up | 12 | 0 | 
| leave over | 12 | 0 | 
| drum up | 12 | 0 | 
| pile up | 12 | 0 | 
| go around | 12 | 7 | 
| close in | 12 | 3 | 
| go away | 12 | 0 | 
| shrug off | 12 | 0 | 
| let in | 12 | 0 | 
| call out | 11 | 2 | 
| pull up | 11 | 0 | 
| pull in | 11 | 3 | 
| bite off | 11 | 0 | 
| break through | 11 | 11 | 
| knock down | 11 | 0 | 
| piss off | 11 | 0 | 
| tone down | 11 | 0 | 
| play along | 11 | 0 | 
| call back | 11 | 0 | 
| follow through | 11 | 0 | 
| get back | 11 | 0 | 
| strike up | 11 | 0 | 
| vote down | 11 | 0 | 
| join in | 11 | 31 | 
| blow out | 11 | 2 | 
| carve out | 11 | 0 | 
| face up | 11 | 3 | 
| hole up | 11 | 0 | 
| fight back | 11 | 0 | 
| leave behind | 11 | 2 | 
| wash up | 11 | 0 | 
| stock up | 11 | 0 | 
| knock out | 11 | 2 | 
| cobble together | 11 | 0 | 
| shape up | 11 | 0 | 
| settle down | 10 | 0 | 
| draw out | 10 | 0 | 
| measure up | 10 | 0 | 
| bogge down | 10 | 0 | 
| phase out | 10 | 0 | 
| spice up | 10 | 0 | 
| carry off | 10 | 1 | 
| divide up | 10 | 0 | 
| write down | 10 | 0 | 
| shut off | 10 | 0 | 
| do away | 10 | 0 | 
| mete out | 10 | 0 | 
| pay down | 10 | 0 | 
| go in | 10 | 27 | 
| blow off | 10 | 2 | 
| chime in | 10 | 0 | 
| head off | 10 | 0 | 
| stand in | 10 | 68 | 
| leave aside | 10 | 0 | 
| sit out | 10 | 0 | 
| pump up | 10 | 0 | 
| set about | 10 | 0 | 
| spill over | 10 | 1 | 
| pull down | 10 | 0 | 
| own up | 10 | 1 | 
| knock off | 10 | 2 | 
| go over | 9 | 18 | 
| ward off | 9 | 0 | 
| rub off | 9 | 0 | 
| hammer out | 9 | 0 | 
| burn up | 9 | 0 | 
| talk up | 9 | 0 | 
| pay up | 9 | 0 | 
| roll up | 9 | 0 | 
| drag out | 9 | 0 | 
| chip in | 9 | 0 | 
| shoot up | 9 | 0 | 
| take down | 9 | 1 | 
| put together | 9 | 0 | 
| branch out | 9 | 1 | 
| drive down | 9 | 1 | 
| squeeze out | 9 | 1 | 
| set down | 9 | 0 | 
| loosen up | 9 | 0 | 
| burn down | 9 | 0 | 
| stack up | 9 | 0 | 
| beat out | 9 | 1 | 
| run off | 9 | 0 | 
| throw off | 9 | 2 | 
| come away | 9 | 0 | 
| blurt out | 9 | 0 | 
| dish out | 9 | 0 | 
| tip off | 9 | 0 | 
| stay up | 9 | 0 | 
| play off | 9 | 2 | 
| fork over | 9 | 0 | 
| stick up | 9 | 0 | 
| mull over | 9 | 2 | 
| pour in | 9 | 0 | 
| water down | 9 | 0 | 
| drag down | 8 | 0 | 
| explain away | 8 | 0 | 
| touch down | 8 | 0 | 
| spin out | 8 | 4 | 
| order up | 8 | 0 | 
| calm down | 8 | 0 | 
| rattle off | 8 | 0 | 
| win out | 8 | 0 | 
| fall down | 8 | 4 | 
| sit around | 8 | 4 | 
| start over | 8 | 2 | 
| spread out | 8 | 0 | 
| plug in | 8 | 1 | 
| crack up | 8 | 0 | 
| free up | 8 | 0 | 
| carry over | 8 | 0 | 
| rat out | 8 | 0 | 
| sweep up | 8 | 0 | 
| siphon off | 8 | 0 | 
| pour out | 8 | 3 | 
| fool around | 8 | 0 | 
| gun down | 8 | 0 | 
| play down | 8 | 0 | 
| throw away | 8 | 0 | 
| drag on | 8 | 0 | 
| pull over | 8 | 0 | 
| eat up | 8 | 0 | 
| lose out | 8 | 1 | 
| eat away | 8 | 0 | 
| put forth | 8 | 0 | 
| touch off | 8 | 0 | 
| pile on | 8 | 3 | 
| lighten up | 8 | 0 | 
| snatch up | 8 | 0 | 
| toss in | 7 | 2 | 
| sink in | 7 | 2 | 
| stay on | 7 | 27 | 
| straighten out | 7 | 0 | 
| heat up | 7 | 0 | 
| toss out | 7 | 1 | 
| scoop up | 7 | 0 | 
| stand by | 7 | 46 | 
| bring back | 7 | 0 | 
| give off | 7 | 0 | 
| fess up | 7 | 0 | 
| bear out | 7 | 7 | 
| tack on | 7 | 1 | 
| summon up | 7 | 0 | 
| think up | 7 | 1 | 
| cut up | 7 | 0 | 
| rev up | 7 | 0 | 
| beat back | 7 | 0 | 
| kick up | 7 | 0 | 
| stretch out | 7 | 0 | 
| hold down | 7 | 0 | 
| match up | 7 | 0 | 
| shake off | 7 | 0 | 
| bend over | 7 | 4 | 
| toss off | 7 | 0 | 
| step in | 7 | 5 | 
| snap up | 7 | 0 | 
| root out | 7 | 0 | 
| bind up | 7 | 0 | 
| whip out | 7 | 0 | 
| ferret out | 7 | 0 | 
| bounce back | 7 | 0 | 
| zero in | 7 | 0 | 
| look down | 7 | 1 | 
| live on | 7 | 49 | 
| tune out | 7 | 0 | 
| type in | 7 | 0 | 
| round out | 7 | 0 | 
| weed out | 7 | 0 | 
| win back | 7 | 0 | 
| try out | 7 | 0 | 
| cool off | 7 | 0 | 
| carve up | 7 | 0 | 
| gin up | 7 | 0 | 
| strike out | 7 | 0 | 
| blot out | 7 | 0 | 
| freak out | 7 | 0 | 
| keep out | 7 | 2 | 
| swear off | 7 | 1 | 
| hash out | 7 | 0 | 
| fight off | 7 | 0 | 
| get through | 7 | 19 | 
| fesse up | 7 | 0 | 
| screw around | 7 | 0 | 
| fire up | 7 | 0 | 
| play around | 7 | 1 | 
| leave off | 7 | 3 | 
| dredge up | 7 | 0 | 
| spit out | 7 | 0 | 
| camp out | 7 | 0 | 
| lead off | 7 | 0 | 
| dumbe down | 7 | 0 | 
| tear off | 7 | 0 | 
| bow out | 6 | 3 | 
| tangle up | 6 | 0 | 
| flatten out | 6 | 0 | 
| get down | 6 | 1 | 
| burn out | 6 | 1 | 
| pipe up | 6 | 0 | 
| wind down | 6 | 0 | 
| let up | 6 | 0 | 
| send up | 6 | 1 | 
| draw down | 6 | 0 | 
| pack up | 6 | 0 | 
| soak up | 6 | 0 | 
| perk up | 6 | 0 | 
| swallow up | 6 | 0 | 
| preside over | 6 | 60 | 
| deck out | 6 | 0 | 
| sit up | 6 | 0 | 
| link up | 6 | 0 | 
| read on | 6 | 15 | 
| blow over | 6 | 3 | 
| mess around | 6 | 0 | 
| face off | 6 | 0 | 
| leak out | 6 | 1 | 
| look back | 6 | 0 | 
| tear up | 6 | 0 | 
| freeze out | 6 | 2 | 
| dust off | 6 | 0 | 
| settle in | 6 | 7 | 
| draw in | 6 | 7 | 
| sketch out | 6 | 0 | 
| beat down | 6 | 0 | 
| sit in | 6 | 95 | 
| lift up | 6 | 0 | 
| run around | 6 | 6 | 
| turn back | 6 | 0 | 
| shut out | 6 | 7 | 
| wait around | 6 | 0 | 
| start up | 6 | 0 | 
| trade in | 6 | 4 | 
| buckle up | 6 | 0 | 
| chickene out | 6 | 1 | 
| bid up | 6 | 0 | 
| run over | 6 | 6 | 
| beef up | 6 | 0 | 
| face down | 6 | 0 | 
| gum up | 6 | 0 | 
| nibble away | 6 | 0 | 
| buy out | 6 | 0 | 
| roll back | 6 | 0 | 
| log off | 6 | 0 | 
| force out | 6 | 4 | 
| top off | 6 | 0 | 
| dig out | 6 | 0 | 
| serve out | 6 | 0 | 
| iron out | 6 | 0 | 
| crank out | 5 | 0 | 
| cross over | 5 | 1 | 
| count on | 5 | 63 | 
| get around | 5 | 15 | 
| throw around | 5 | 1 | 
| choke away | 5 | 0 | 
| want out | 5 | 0 | 
| hit up | 5 | 0 | 
| pan out | 5 | 0 | 
| tap out | 5 | 0 | 
| par down | 5 | 0 | 
| do in | 5 | 168 | 
| finish up | 5 | 0 | 
| fall out | 5 | 16 | 
| brasse off | 5 | 0 | 
| eat out | 5 | 0 | 
| dress down | 5 | 0 | 
| brush up | 5 | 0 | 
| build in | 5 | 18 | 
| give back | 5 | 0 | 
| put away | 5 | 0 | 
| ponie up | 5 | 0 | 
| rain down | 5 | 0 | 
| pay back | 5 | 0 | 
| dash off | 5 | 0 | 
| think out | 5 | 1 | 
| drop by | 5 | 14 | 
| turn away | 5 | 0 | 
| haul in | 5 | 0 | 
| fall off | 5 | 10 | 
| mix in | 5 | 2 | 
| fix up | 5 | 0 | 
| snuff out | 5 | 0 | 
| set in | 5 | 72 | 
| gobble up | 5 | 0 | 
| bring along | 5 | 0 | 
| set back | 5 | 0 | 
| while away | 5 | 0 | 
| keep off | 5 | 2 | 
| tease out | 5 | 0 | 
| ante up | 5 | 0 | 
| phase in | 5 | 0 | 
| move up | 5 | 2 | 
| sniff out | 5 | 0 | 
| hem in | 5 | 0 | 
| switch over | 5 | 0 | 
| tot up | 5 | 0 | 
| pack in | 5 | 2 | 
| haul out | 5 | 0 | 
| load up | 5 | 0 | 
| sound off | 5 | 0 | 
| mail out | 5 | 0 | 
| rough up | 5 | 0 | 
| finish off | 5 | 0 | 
| set aside | 5 | 0 | 
| rustle up | 5 | 0 | 
| bandy about | 5 | 1 | 
| factor in | 5 | 3 | 
| push up | 5 | 0 | 
| curl up | 5 | 1 | 
| star down | 5 | 1 | 
| suit up | 5 | 0 | 
| strip away | 5 | 0 | 
| dig in | 5 | 1 | 
| plunk down | 5 | 0 | 
| fall through | 5 | 6 | 
| join up | 5 | 0 | 
| leave open | 5 | 0 | 
| shout down | 5 | 0 | 
| hang around | 5 | 15 | 
| sweep away | 5 | 0 | 
| wise up | 5 | 0 | 
| drive off | 5 | 1 | 
| hunker down | 5 | 0 | 
| boot up | 5 | 0 | 
| check off | 5 | 0 | 
| squeeze in | 5 | 0 | 
| edge out | 5 | 1 |
