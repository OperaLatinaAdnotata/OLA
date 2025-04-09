# Syntactic Annotation

The syntax was annotated following the guidelines:

* https://github.com/PerseusDL/treebank_data/blob/master/v1/greek/docs/guidelines.pdf
* https://github.com/PerseusDL/treebank_data/blob/master/AGDT2/guidelines/Greek_guidelines.md

The list of the syntactic labels is: 
SBJ, AuxY, PRED, ATV, ATR, AuxX, AuxC, AuxZ, OBJ, ADV, APOS, PNOM, COORD, AuxK,
AuxP, AtvV, AuxV, ExD, OCOMP, AuxG, AuxΖ, AuxΚ (mistaken labels found in the 
treebank: "Aux", "XSEG", "_CO", "_ExD0_PRED_CO", "CO").

Note that the root of a syntactic tree is only one token (therefore,
punctuation marks, as well as other nodes,
which in the original AGLDT annotation scheme are
dependents of the root, were made dependents of the first node
that depends on the root,
which usually corresponds to the main verb
of a sentence or a coordinate conjunction).
