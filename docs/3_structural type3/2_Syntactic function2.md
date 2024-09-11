# 3-2. noun phrase constituent: modifier

## 3-2-1. attributive adjectives as noun pre-modifier
1. Descriptions
   - Attributive adjectives are adjectives describing particular attributes of the noun they modify.
   - They are pre-modifiers because they come before the noun they modify.
   - This category excludes cases where an attributive adjective serves as a complement to a copular verb (e.g., *this project is **good***)
2. Tag
   - `attr+npremod` is tagged on the attributive **adjective**.
   - In cases where multiple adjectives are included, tag each one (as in the third example below).
3. Examples
   - *He struggled to read the <ins>**emotional**</ins> inquiry.* 
   - *She drives a very <ins>**fast**</ins> car.*
   - *The <ins>**small**, **antique**, **wooden** chest</ins> held many treasures.*
   - *They bought a <ins>**beautiful**</ins> home.*
4. Discussions
   - **Q:** How should we treat the post-modifier adjective? (e.g., *He is a man **confident** of his capacity.*)


## 3-2-2. noun as noun pre-modifier
1. Descriptions
   - Nouns as noun pre-modifiers (sometimes *noun adjunct*) are nouns that add specific information to the following noun.
   - These nouns often communicate meaning related the purpose, type, ownership, or material among other qualities of nouns they modify.
2. Tag
   - `nn+npremod` is tagged on the pre-modifying **noun**. 
3. Examples
   - *The pilot's license needed to be reviewed by the <ins>**avitation**</ins> security committee.*
   - *He barely passed <ins>**fighter**</ins> pilot training.*
   - *She placed her <ins>**coffee**</ins> cup on the table.*
   - *The city council is considering a new <ins>**traffic**</ins> regulation proposal.*
4. Discussions
   - We tagged instances where proper nouns function as pre-modifiers in a noun phrase.
      - In such cases, only the last part of the proper noun phrases is tagged (e.g., *the <ins>Second World **War**</ins> decades*).
      - When the proper noun is part of a coordinated structure, only the first proper noun is tagged (e.g., *the <ins>**Reform** and Conservative</ins> era*).
   - We did NOT tag numeric modifers (e.g., *eighty four hours*)

## 3-2-3. *of* phrases as noun
1. Descriptions
   - *of* phrases modify nouns and articulate a variety of relationships between nouns, linked by *of*. These phrases follow the noun they modify, serving as a post-modifer. They can indicate relationships including possession (i.e., genitive, part-whole, association, or classification.
   - The *of* phrase comes after the noun it relates to, therefore being considered a post-modifier.
2. Tag
   - `of+npostmod` is tagged on the **of** of the *of* phrase.
3. Examples
   - *The sound <ins>**of** music</ins> was soothing.*
   - *McKenna wrote about the origins <ins>**of** human language.</ins>*
   - *She is the CEO <ins>**of** the company.</ins>*
   - *A group <ins>**of** students</ins> gathered in the hall.*
   - *The title <ins>**of** the book</ins> is harry potter and the cursed child.*
   - *... a war <ins>**of** words</ins>*
   
## 3-2-4. other prepositional phrases as noun
1. Descriptions
   - This tag includes all other prepositional phrases (except for *of*) that follow a noun and modify it.
2. Tag
   - `in+npostmod` is tagged on the **preposition** of the prepositional phrase.
3. Examples
   - *The painting <ins>**in** the corner</ins> caught my eye.*
   - *The conference <ins>**on** global warming</ins> was very informative.*
   - *Your cake <ins>**with** chocolate icing</ins> was delicious.*
   - *Children <ins>**under** twelve</ins> get in for free.*

## 3-2-5. appositive noun phrases as noun
1. Descriptions
   - Noun phrases in apposition (appositive) have equivalent status with the preceding (head) noun phrase.
       - The order of the head noun phrase and the appositive could (nomally) be reversed to produce an equal grammatical construction with basically the same meaning.
   - They provide descriptive information about the head noun but are not needed to identify the reference of the head noun.
2. Tag
   - `appos+npostmod` is tagged on the head **noun** of the appositive phrase. 
3. Examples
   - *The capital city, <ins>**Paris**</ins>, is the heart of France.*
       - *Paris, <ins>the capital **city**</ins>, is the heart of France.* 
   - *The famous inventor <ins>Thomas **Edison**</ins> made numerous advancements in technology.* (Notes. When the noun phrase is a proper noun, we tag on the last name.)
       - *Thomas Edison, <ins>the famous **inventor**</ins>, made numerous advancements in technology.*
   - *My brother <ins>**John**</ins> is a painter.*
   - *My friend, <ins>an experienced **hiker**,</ins> has traveled far and wide.*
