# hausa
Repository for Hausa NLP tools

## Part of speech tagger model
hausa_model.par
Version 2.0

A simple part-of-speech tagging model for Hausa in Boko orthography, for use with the freely available TreeTagger:
http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/
 
Portmanteau tags are used in orthographic words fusing two part of speech categories (see below).

### Basic tags
* ADJ	adjective
* ADV	adverb
* CONJ	conjunction
* EXIST	existential verboid (akwai, babu)
* FM	foreign material (not Hausa)
* FOC	focus marker / copula (ne, ce)
* FUT	future marker (za)
* INTJ	interjection
* LINK	linking na or ta ('of')
* N	noun
* NEG	negation
* NUM	numeral
* PAC	person-aspect complex (e.g. ya-)
* PDEM	demonstrative
* PIND	indefinite pronoun
* PINT	interrogative
* PPOS	possessive pronoun
* PPRS	personal pronoun
* PREL	relative pronoun
* PROG	progressive person aspect complex (e.g. ina-, nake-)
* PRP	preposition
* PTC	particle
* PUNCT	punctuation
* QUANT	quantifier
* V	verb

### Portmanteau tags
* FUT_PAC fused future + PAC marker (zai, zan)
* NEG_PAC	PAC fused with negation (e.g. ban)
* PAC_V	fused PAC and verb form (e.g. yayi, spelled together)
* PPRS_FOC	fused personal pronoun + copula spelled together (shine)
* PPRS_PROG	fused personal pronoun + progressive PAC (shike)
* PREL_PAC	fused relative + PAC  (daya)
* PREL_PROG	fused relative + progressive PAC  (dake)
* PROG_ADV	fused progressive person aspect complex + ADV (e.g. kenan)
