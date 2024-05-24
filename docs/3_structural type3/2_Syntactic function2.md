# 3-2. noun phrase constituent: modifier

*under construction* 

## 3-2-1. attributive adjectives as noun pre-modifier
1. Descriptions
   - Attributive adjectives are adjectives describing particular attributes of the noun they modify.
   - They are pre-modifiers because they come before the noun they modify.
   - This category excludes cases where an attributive adjective serves as a complement to a copular verb (e.g., *this project is **good***)
2. Tag
   - `attr+nn+premod` is tagged on the attributive **adjective**.
   - In cases where multiple adjectives are included, tag each one (as in the third example below) HS: **Please check this during the discussion!**
3. Examples
   - *He struggled to read the <ins>**emotional**</ins> inquiry.* 
   - *She drives a <ins>**fast**</ins> car.*
   - *The <ins>**small**</ins>, <ins>**antique**</ins> <ins>**wooden**</ins> chest held many treasures.*
   - *They bought a <ins>**beautiful**</ins> home.

## 3-2-2. noun as noun pre-modifier
1. Descriptions
   - Nouns as noun pre-modifiers (sometimes *noun adjunct*) are nouns that add specific information to the following noun.
   - These nouns often communicate meaning related the purpose, type, ownership, or material among other qualities of nouns they modify.
2. Tag
   - `nn+npremod` is tagged on the pre-modifying **noun**. 
3. Examples
   - *The pilot's license needed to be reviewed by the <ins>**avitation** security</ins> committee.*
   - *He barely passed <ins>**fighter** pilot</ins> training.*
   - *She placed her <ins>**coffee**</ins> cup on the table.*
   - *The city council is considering a new <ins>**traffic** regulation</ins> proposal.*

## 3-2-3. *of* genitive phrases as noun post-modifier
1. Descriptions
   - *of* genitive phrases can modify nouns and express relationship between nouns, linked by *of.*
   - The *of* genetive phrase comes after the noun it relates to, therefore being considered a post-modifier.
2. Tag
   - `of+gen+post+nmod` is tagged on the **of** of the *of* genitive phrase.
   - *need to change this to 'of+gen+post+nmod'* 2024-05-24
3. Examples
   - *The sound <ins>**of** music</ins> was soothing.*
   - *McKenna wrote about the origins <ins>**of** human language.</ins>*
   - *She is the CEO <ins>**of** the company.</ins>*
   - *A group <ins>**of** students</ins> gathered in the hall.*
4. Question
   - HS: I am not sure how to treat the pronoun+*of*+NP cases (e.g., a lot of you, each of you, many of you...)
   
## 3-2-4. other prepositional phrases as noun post-modifier
1. Descriptions
   - This tag includes all other prepositional phrases (except for *of*) that follow a noun and modify it.
2. Tag
   - `in+post+nmod` is tagged on the **preposition** of the prepositional phrase.
3. Examples
   - *The painting <ins>**in** the corner</ins> caught my eye.*
   - *The conference <ins>**on** global warming</ins> was very informative.*
   - *Your cake <ins>**with** chocolate icing</ins> was delicious.*
   - *Children <ins>**under** twelve</ins> get in for free.*

## 3-2-5. appositive noun phrases as noun post-modifier
1. Descriptions
   - Noun phrases in apposition (appositive) have equivalent status with the preceding (head) noun phrase.
       - The order of the head noun phrase and the appositive could (nomally) be reversed to produce an equal grammatical construction with basically the same meaning.
   - They provide descriptive information about the head noun but are not needed to identify the reference of the head noun.
2. Tag
   - `nn+nappos` is tagged on the head **noun** of the appositive phrase. 
3. Examples
   - *The capital city, <ins>**Paris**</ins>, is the heart of France.*
       - *Paris, <ins>the capital **city**</ins>, is the heart of France.* 
   - *The famous inventor <ins>**Thomas Edison**</ins> made numerous advancements in technology.* (Q. If it's a proper noun, where do we need to tag?)
       - *Thomas Edison, <ins>the famous **inventor**</ins>, made numerous advancements in technology.*
   - *My brother <ins>**John**</ins> is a painter.*
   - *My friend, <ins>an experienced **hiker**,</ins> has traveled far and wide.*
