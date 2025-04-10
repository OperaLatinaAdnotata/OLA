# Opera Latina Adnotata v0.2.0

This repository contains the largest open access annotated corpus
of Latin texts, **Opera Latina Adnotata** 🏋️❤️😃:

* number of base texts: 736, each corresponding to an ancient work
* number of tokens: 17,919,596

The base texts come from the following repositories:

* [canonical-latinLit](https://github.com/PerseusDL/canonical-latinLit/releases/tag/0.0.12144726697)
* [csel-dev](https://github.com/OpenGreekAndLatin/csel-dev/releases/tag/0.0.3678995538)
* [Latin](https://github.com/OpenGreekAndLatin/Latin/releases/tag/v1.14.0)
* [digiliblt](https://github.com/lascivaroma/digiliblt/releases/tag/0.0.67)
* [priapea](https://github.com/lascivaroma/priapeia/releases/tag/1.1.18)
* [additional-texts](https://github.com/lascivaroma/additional-texts/releases/tag/1.0.195)

Because of the large corpus size, the data is made available on Zenodo at:

* [https://doi.org/10.5281/zenodo.15183688](https://doi.org/10.5281/zenodo.15183688)

and can be queried at:

* [https://annis.varro.informatik.uni-leipzig.de/ola020](https://annis.varro.informatik.uni-leipzig.de/ola020)

The present repository allows updates and tracking issues. The corpus can be queried by:

1. word form (i.e., token)
2. lemma
3. morphology (POS and morphological features)
4. syntax (dependency syntax following the AGDT annotation scheme)
5. CTS URN for work, author, and edition
6. CTS structure for each work (e.g., "book," "section," etc.) 
6. author name
7. work title
8. (experimental) IPA transcription of word forms (the Classical Latin one)

The morphosyntactic annotation was performed using Latinpipe, whose model
can be dowloaded from [Hugging Face](https://huggingface.co/bowphs/latinpipe-evalatin/tree/main)
(thanks to F. Riemenschneider).
The test set results are:

|POS|Feats|ALLTags|UAS|LAS|Lemmas|
|-----|----|----|----|----|----|
|97.15|93.30|91.53|84.10|77.53|91.38|

The annotations for CTS URN, CTS structure, author name, and work title were
retrieved automatically from the original texts (and therefore they may
contain errors and inconsistencies).

The IPA transcription is based on a ByT5 model that achieved an accuracy
of **0.83** (correct IPA transcriptions) on Greek and Latin data 
from Wiktionary. The IPA transcription is the "Classical Latin" one.

The repository is organized as follows (further details within each folder):
1. `abbreviations` contains a file useful for tokenization.
2. `annotation_example` contains an unzipped example of the
annotation layers, which is useful for inspection.
3. `query` contains documentation to query the corpus in
[ANNIS](https://annis.varro.informatik.uni-leipzig.de/ola020).
4. `tokenize` contains files used for tokenization.
5. `urn_cts` contains files with bibliographic information about the texts.



## Citation

```
Giuseppe G. A. Celano. 2025. Opera Latina Adnotata (v0.2.0). Zenodo.
https://doi.org/10.5281/zenodo.15183688.
```

```
@misc{celanoOLA020,
author =    {Giuseppe G. A. Celano},
title =     {Opera Latina Adnotata},
year =      {2025},
publisher = {Zenodo},
version =   {v0.2.0},
doi =       {10.5281/zenodo.15183688},
url =       {https://doi.org/10.5281/zenodo.15183688}
}
```
## Contact
Dr. Giuseppe G. A. Celano<br/>
Universität Leipzig<br/>
Institute of Computer Science<br/>
Augustusplatz 10<br/>
04109 Leipzig<br/>
Deutschland<br/>
*mysurname* at informatik.uni-leipzig.de<br/>

## Funder

<a href="http://www.dfg.de/index.jsp" target="_blank">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/86/DFG-logo-blau.svg" 
width="" height="40" alt=""/>
</a>

(Project number: 408121292)

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" 
src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br/>
This work is licensed under a <a rel="license" 
href="http://creativecommons.org/licenses/by-sa/4.0/">
Creative Commons Attribution-ShareAlike 4.0 International License</a> (for more
details, look also at the repositories of the base texts mentioned above).
