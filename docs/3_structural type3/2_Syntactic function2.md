# 3-2. noun phrase constituent: modifier

## 3-2-1. attributive adjectives as noun pre-modifier
1. Descriptions
   - Attributive adjectives are adjectives describing particular attributes of the noun they modify.
   - They are pre-modifiers because they come before the noun they modify.
   - This category excludes cases where an attributive adjective serves as a complement to a copular verb (e.g., *this project is **good***)
2. Tag
   - `attr+npremod` is tagged on the attributive **adjective**.
   - In cases where multiple adjectives are included, tag each one (as in the third example below) HS: **Please check this during the discussion!**
3. Examples
   - *He struggled to read <ins>the **emotional** inquiry</ins>.* 
   - *She drives <ins>a **fast** car</ins>.*
   - *<ins>The **small**, **antique** <ins>**wooden** chest</ins> held many treasures.*
   - *They bought <ins>a **beautiful** home</ins>.*

## 3-2-2. noun as noun pre-modifier
1. Descriptions
   - Nouns as noun pre-modifiers (sometimes *noun adjunct*) are nouns that add specific information to the following noun.
   - These nouns often communicate meaning related the purpose, type, ownership, or material among other qualities of nouns they modify.
2. Tag
   - `nn+npremod` is tagged on the pre-modifying **noun**. 
3. Examples
   - *The pilot's license needed to be reviewed by <ins>the **avitation** security committee</ins>.*
   - *He barely passed <ins>**fighter** pilot training</ins>.*
   - *She placed <ins>her **coffee** cup</ins> on the table.*
   - *The city council is considering <ins>a new **traffic** regulation proposal</ins>.*
4. Discussions
   - We tagged instances where proper nouns function as pre-modifiers in a noun phrase.
      - In such cases, only the last part of the proper noun phrases is tagged (e.g., *the Second World **War** decades*).
      - When the proper noun is part of a coordinated structure, only the first proper noun is tagged (e.g., *the **Reform** and Conservative era*).
   - We did NOT tag numeric modifers (e.g., *eighty four hours*)

## 3-2-3. *of* phrases as noun post-modifier
1. Descriptions
   - *of* phrases modify nouns and articulate a variety of relationships between nouns, linked by *of*. These phrases follow the noun they modify, serving as a post-modifer. They can indicate relationships other than possession (i.e., genitive), such as part-whole, association, or classification.
   - The *of* phrase comes after the noun it relates to, therefore being considered a post-modifier.
2. Tag
   - `of+npostmod` is tagged on the **of** of the *of* phrase.
3. Examples
   - *<ins>The sound **of** music</ins> was soothing.*
   - *McKenna wrote about <ins>the origins **of** human language.</ins>*
   - *She is <ins>the CEO **of** the company.</ins>*
   - *<ins>A group **of** students</ins> gathered in the hall.*
   - *<ins>The title **of** the book</ins> is harry potter and the cursed child.*
   - *... <ins>a war **of** words</ins>*
   
## 3-2-4. other prepositional phrases as noun post-modifier
1. Descriptions
   - This tag includes all other prepositional phrases (except for *of*) that follow a noun and modify it.
2. Tag
   - `in+npostmod` is tagged on the **preposition** of the prepositional phrase.
3. Examples
   - *<ins>The painting **in** the corner</ins> caught my eye.*
   - *<ins>The conference **on** global warming</ins> was very informative.*
   - *<ins>Your cake **with** chocolate icing</ins> was delicious.*
   - *<ins>Children **under** twelve</ins> get in for free.*

## 3-2-5. appositive noun phrases as noun post-modifier
1. Descriptions
   - Noun phrases in apposition (appositive) have equivalent status with the preceding (head) noun phrase.
       - The order of the head noun phrase and the appositive could (nomally) be reversed to produce an equal grammatical construction with basically the same meaning.
   - They provide descriptive information about the head noun but are not needed to identify the reference of the head noun.
2. Tag
   - `appos+npostmod` is tagged on the head **noun** of the appositive phrase. 
3. Examples
   - *<ins>The capital city, **Paris**</ins>, is the heart of France.*
       - *<ins>Paris, the capital **city**</ins>, is the heart of France.* 
   - *<ins>The famous inventor Thomas **Edison**</ins> made numerous advancements in technology.* (Q. When the noun phrase is a proper noun, we tag on the last name.)
       - *<ins>Thomas Edison, the famous **inventor**</ins>, made numerous advancements in technology.*
   - *<ins>My brother **John**</ins> is a painter.*
   - *<ins>My friend, an experienced **hiker**,</ins> has traveled far and wide.*
