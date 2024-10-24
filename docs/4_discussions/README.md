---
sort: 1
---

# Discussions
This section includes some of the pre-processing rules we discussed based on the functionality of the tagger.

## Semi-modals 

The following semi-modals were pre-processed before parsing and tagging sentence structures: *have to, had to, got to, have/had got to, gotta, ought to, BE supposed to, BE going to, gonna, BE about to,* and *used to.* These were incorporated in the updated versions.

**Notes:**
1. BE includes all its inflected forms for person and tense.
2. *used to* is treated as a semi-modal only when it is **not** preceded by BE.

## Passive

We tagged the **passive** construction, not the *be*-verb itself.

- *They knew <ins>what they were going to be **asked**.</ins>* (verb-*wh*-complement)

## Coordination

We tagged the first main verb, not the subsequent verbs.

- *A truck driver <ins>who just **slammed** and kicked at everything</ins>* (noun-finite relative clause)