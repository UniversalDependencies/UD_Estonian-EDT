# Summary

UD Estonian is a converted version of the Estonian Dependency Treebank (EDT), originally annotated in the Constraint Grammar (CG) annotation scheme, and consisting of genres of fiction, newspaper texts and scientific texts. The treebank contains 30,972 trees, 437,769 tokens.


# Introduction

The Estonian UD EDT treebank is based on the [Estonian Dependency Treebank](https://github.com/EstSyntax/) (EDT), created at the University of Tartu. The treebank has been automatically converted and then manually reviewed and reannotated.

The treebank covers 3 different genres, namely newspaper texts, fiction and scientific texts:

* fiction (67,744 tokens, 5,522 sentences)
* newspapers (266,806 tokens, 18,690 sentences)
* scientific texts (94,022 tokens, 5,483 sentences)
* Also, the subpart of Estonian part of HamleDT 3.0 treebank has been reannotated and included in the treebank; it contains 9,200 tokens in 1277 sentences.


# Acknowledgments

We wish to thank all who have contributed to the original EDT annotation effort, especially Eleri Aedmaa, Riin Kirt and Dage Särg.

We also thank developers of [udapi](http://udapi.github.io/), [ud annotatrix](https://github.com/jonorthwash/ud-annotatrix) and , and [ConlluEditor](https://github.com/Orange-OpenSource/conllueditor) tools.

This work was financed by the [National Programme for Estonian Language Technology](https://www.keeletehnoloogia.ee/en?set_language=en) and Estonian Ministery of Education and Research (grant 20-56 IUT20-56 "Computational models for Estonian").

# References

* Kadri Muischnek, Kaili Müürisep, Tiina Puolakainen, Eleri Aedmaa, Riin Kirt, Dage Särg.  2014.
  [Estonian Dependency Treebank and its annotation scheme](http://tlt13.sfs.uni-tuebingen.de/tlt13-proceedings.pdf). In: Proceedings of the 13th Workshop on Treebanks and Linguistic Theories (TLT13), pp. 285–291, ISBN 978-3-9809183-9-8, Tübingen, Germany.
* Kadri Muischnek, Kaili Müürisep and Tiina Puolakainen 2016. Estonian Dependency Treebank: from Constraint Grammar tagset to Universal Dependencies. - Proceedings of LREC 2016.
* Kadri Muischnek and Kaili Müürisep. 2017. Estonian copular and existential constructions as an UD annotation problem. In Proceedings of the NoDaLiDa 2017 Workshop on Universal Dependencies (UDW 2017), pp. 79-85. 2017.

# Changelog

* UD v2.10: annotation of enhanced dependencies improved,  subjects of clausal complements (xcomp) are annotated, regardless of whether this subject is the same or different from the subject of the next higher clause; errors of goeswith annotation fixed, annotation of foreign words improved.
* UD v2.8: Morphological annotation of numerals has been improved, also better documentation has been included
* UD v2.6: In the enhanced representation, 0-nodes have been added in clauses in which a predicate is elided, and the relative pronoun has been attached to its antecedent with the relation 'ref'.
* UD v2.5: Various individual annotation errors and inconsistencies solved. 3527 tokens added to training data.
* UD v2.4: xcomp function rechecked, some fixed constructions added. Various individual annotatation errors and inconsistencies solved.
* UD v2.3: more data added to v2.2. Now the whole original EDT is included in Estonian UD. Annotation of elliptical constructions (label 'orphan') is more systematic. Various individual annotation errors and inconsistencies solved.
* UD v2.2: more data added to v2.1; fixed errors in v2.1 files; repository renamed from UD_Estonian to UD_Estonian-EDT.
* UD v2.1: manual reannotation of copula sentences, names and appositions; semiautomatic reannotation of pronouns and determiners and coordinated structures; automatic reannotation of nmod and obl functions.
* UD v2.0: manual reannotation of copula sentences, names and appositions; semiautomatic reannotation of pronouns and determiners and coordinated structures; automatic reannotation of nmod and obl functions.
* UD v1.2 contained Arborest, a much smaller and older VISL-style treebank. It has been re-annotated and added to EDT for UD v1.3.

<pre>
=== Machine-readable metadata =================================================
Documentation status: stub
Data source: semi-automatic
Data available since: UD v1.2
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: fiction news nonfiction academic
Lemmas: converted from manual
UPOS: converted from manual
XPOS: converted from manual
Features: converted from manual
Relations: converted from manual
Contributing: here
Contributors: Muischnek, Kadri; Müürisep, Kaili; Puolakainen, Tiina; Rääbis, Andriela; Torga, Liisi
Contact: kadri.muischnek@ut.ee, kaili.muurisep@ut.ee
===============================================================================
</pre>
