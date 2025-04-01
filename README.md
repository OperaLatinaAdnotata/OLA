# Opera Latina Adnotata v0.2.0

This repository contains the largest open access annotated corpus
of Latin texts, **Opera Latina Adnotata** (base texts: 736 files
and 17,919,596 tokens) 🏋️❤️😃.

The base texts come from the following repositories:

* [canonical-latinLit](https://github.com/PerseusDL/canonical-latinLit/releases/tag/0.0.12144726697)
* [csel-dev](https://github.com/OpenGreekAndLatin/csel-dev/releases/tag/0.0.3678995538)
* [Latin](https://github.com/OpenGreekAndLatin/Latin/releases/tag/v1.14.0)
* [digiliblt](https://github.com/lascivaroma/digiliblt/releases/tag/0.0.67)
* [priapea](https://github.com/lascivaroma/priapeia/releases/tag/1.1.18)
* [additional-texts](https://github.com/lascivaroma/additional-texts/releases/tag/1.0.195)

Because of the large corpus size, the data is made available on Zenodo at:

* to-add

and can be queried at:

* [https://annis.varro.informatik.uni-leipzig.de/ola020](https://annis.varro.informatik.uni-leipzig.de/ola020)

The present repository allows updates and tracking issues.

The original Latin texts
have been tokenized, sentence-segmented, and morphosyntactically
annotated using a standoff format (PAULA XML).

The repository is organized as follows (further details within each folder):
1. `abbreviations` contains a file useful for tokenization.
2. `annotation_example` contains an unzipped example of the
annotation layers, which is useful for inspection.
3. `query` contains documentation to query the corpus in
[ANNIS](https://annis.varro.informatik.uni-leipzig.de/ola020).
4. `tokenize` contains files used for tokenization
5. `urn_cts` contains files with bibliographic information about the texts.

## Citation

```
Giuseppe G. A. Celano. 2025. Opera Latina Adnotata (v0.2.0). Zenodo.
https:   ...
```

```
@misc{celanoOLA020,
author =    {Giuseppe G. A. Celano},
title =     {Opera Latina Adnotata},
year =      {2025},
publisher = {Zenodo},
version =   {v0.2.0},
doi =       {...},
url =       {...}
}
```
## Contact
Dr. Giuseppe G. A. Celano<br/>
Universität Leipzig<br/>
Institute of Computer Science, NLP<br/>
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
details, look also at the repositories of the original texts mentioned above).
