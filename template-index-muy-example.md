layout: base
title: 'Munduruku UD'
udver: '2'

# UD for LANGUAGE <span class="flagspan"><img class="flag" src="../../flags/svg/AQ.svg" /></span>


# Mundurukú 

## Tokenization and Word Segmentation

* In general, words are delimited by whitespace characters. Description of exceptions follows.
* According to typographical rules, many punctuation marks are attached to a neighboring word. We always tokenize them as separate tokens (words);
* There is no separate class of adjectives in Mundurukú.



## Morphology

### Tags

This is an overview only. For more detailed discussion and examples, see the list of [Mundurukú POS tags](pos/index.html) 
and [Mundurukú features](feat/index.html).

* Mundurukú uses 16 ofthe 17 universal POS categories. ADJ is not used since there is no separate class of adjectives.
Stative-verbs and possessed nouns behave alike, in a way that is not possible to distinguish them morphologically 
(I am ugly / I have uglyness; ugly boy / boy with uglyness).


### Nominal Features

* Nominal words ([NOUN](), [PROPN]() and [PRON]()) are not marked for [Gender](), and are optionally marked for [Number](). 
* Mundurukú classifiers are real nouns. Gomes (2006) speaks of nouns in classifier function. Nouns (NOUN) in this function 
are tagged cl in the XPOS column. The features of the cl tags are their basic meanings, e.g. *'a* Class=Round. 
* Another way to express existential predication is through the reduplication of a noun with the vowel *e* replacing
the original vowel *xat* 'food' *xaxet* 'there is food'. These nouns receive a marked Redup=ex (reduplication existential) in
the FEATS column.

### Verbal Features

* Verbs have a lexical [Aspect](): imperfective (`Imp`), perfective (`Perf`), iterative (`Iter`). 
* Some lexical roots can not easily be assigned to a  specific lexical category. This is the case with *kake* and *opop*. 
These are tagged as AUX in the UPOS, and v:ex (existential verb) and aux respectively in the XPOS.





## Syntax

*

---
**Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any.

---

## Treebanks

There are [N](../treebanks/LCODE-comparison.html) LANGUAGE UD treebanks:

  * [LANGUAGE-A](../treebanks/LCODE_a/index.html)
  * [LANGUAGE-B](../treebanks/LCODE_b/index.html)

---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
