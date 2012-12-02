sn
==

Semantic Neighbors -- a dataset for semantic similarity measure evaluation

This dataset stems from the work of (Baroni and Lenci, 2011) on the BLESS dataset (Baroni and Lenci Evaluation of Semantic Spaces). This dataset contains a set of semantic relations, such as <agitator, syn, activist>,  <hawk , syn, predator>, <gun, syn, weapon>, <dishwasher, syn, freezer>, <lecture, random, clown>, <driver, random, stone>, and <computer, random,river>. Each **target** term (the first element in the tuple) has roughly the same number of meaningful and random **relatum** terms (the third element in the tuple). 

We built the SN (Semantic Neighbors) dataset in order to complement the BLESS which contains no synonyms. SN relates 462 target nouns to 5,910 relatum words with 14,682  relations (7,341 synonyms and 7,341 are random). The SN contains synonyms coming from three sources: WordNet 3.0 (Miller, 1995), Roget's thesaurus (Kennedy and Szpakowichz, 2008), and a free synonyms database (http://synonyms-database.downloadaces.com/). The relations in the dataset were validated manually.    

Related repositories:
--------------------

- **sim-eval** -- a tool for semantic similarity measure evaluation, which use SN: https://github.com/alexanderpanchenko/sim-eval

Files
-----

- **sn1.csv** -- the initial version of the dataset

- **sn2.csv** -- a cleaned version of this dataset (the recommended version)

- **sn2-voc.csv** -- terms which occur either as targets or relatums in the dataset

- **sn2-targets.csv** -- terms which occur as targets in the dataset

- **sn2-relatums.csv** --  terms which occur as relatums in the dataset

- **sn3-annotations.csv** -- manual annotations of the sn2.csv file (to be integrated)

References
----------

- Miller, G. A. (1995b). Wordnet: a lexical database for english. Communications of ACM, 38(11):39–41.

- Baroni, M. and Lenci, A. (2011). How we blessed distributional semantic evaluation. GEMS (EMNLP), 2011, pages 1–11.

- Kennedy, A. and Szpakowicz, S. (2008). Evaluating rogets thesauri. ACL-08 HLT, pages 416–424.




