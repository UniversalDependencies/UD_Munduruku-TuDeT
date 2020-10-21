layout: base
title: 'Munduruku UD'
udver: '2'

# UD for Mundurukú 

## Tokenization and Word Segmentation

* In general, words are delimited by whitespace characters. Description of exceptions follows.
* According to typographical rules, many punctuation marks are attached to a neighboring word. We always tokenize them as separate tokens (words);
* There is no separate class of adjectives in Mundurukú.



## Morphology

### Tags

This is an overview only. For more detailed discussion and examples, see the list of [Mundurukú POS tags](pos/index.html) 
and [Mundurukú features](feat/index.html).

* Mundurukú uses 16 ofthe 17 universal POS categories. ADJ is not used since there is no separate class of adjectives.
Stative-verbs and adjectives behave alike, in a way that is not possible to distinguish them morphologically 
(I am ugly / I have uglyness; ugly boy / boy with uglyness).


### Nominal Features

* Nominal words ([NOUN](), [PROPN]() and [PRON]()) are not marked for [Gender](), and are optionally marked for [Number](). 
* Mundurukú classifiers are real nouns. Gomes (2006) speaks of nouns in classifier function. Nouns (NOUN) in this function 
are tagged cl in the XPOS column. 

### Existential predication
* n Redup=ex

* Some lexical roots can not easily be assigned to a  specific lexical category. This is the case with *kake* and *opop*. 
These are tagged as AUX in the UPOS, and v:ex (existential verb) and aux respectively in the XPOS.
* Another way to express existential predication is through the reduplication of a noun with the vowel *e* replacing
the original vowel *xat* 'food' *xaxet* 'there is food'.

### Verbal Features



* Verbs have a lexical [Aspect](): imperfective (`Imp`), perfective (`Perf`), iterative (`Iter`). 




### Pronouns, Determiners, Quantifiers


