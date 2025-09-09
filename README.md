
# DANTEStocks

# Summary

DANTEStocks (Di Felippo et al., 2024) is a collection of Brazilian Portuguese tweets on the stock market domain that is part of Porttinari (“PORTuguese Treebank”), which shall be a large multigenre treebank for Portuguese (Pardo et al., 2021), following the "Universal Dependencies" framework (de Marneffe et al., 2021).

# Introduction

The corpus consists of 4,042 tweets and 80,997 tokens. To annotate the corpus according to UD, the entire tweet was taken as a basic unit of analysis, which means that the tweets were not segmented into smaller units as sentences, clauses or phrases. Besides, the tweets were not normalized, containing all phenomena typical to social media text in general and to Twitter in particular. Morphosyntactic (Silva et al., 2021; Di Felippo et al., 2023) and syntactic annotations (Di Felippo et al., 2024) were carried out through alternating steps of automatic processing and manual revision. For the interested reader, DANTEStocks, as well as other related information, may be accessed at [Poetisa Project](https://sites.google.com/icmc.usp.br/poetisa/porttinari).

# Acknowledgements

This work was carried out at the Center for Artificial Intelligence of the University of São Paulo (C4AI - [c4ai.inova.usp.br](http://c4ai.inova.usp.br/)), with support by the São Paulo Research Foundation (FAPESP grant #2019/07665-4) and by the IBM Corporation. The project was also supported by the Ministry of Science, Technology, and Innovation, with resources of Law N. 8.248, of October 23, 1991, within the scope of PPI-SOFTEX, coordinated by Softex and published as Residence in TIC 13, DOU 01245.010222/2022-44.

# Corpus Splitting

The treebank has been randomly split as follows:
- **Train:** 3040 tweets (60932 tokens) (75.2%)
- **Dev:** 501 tweets (10004 tokens) (12.4%)
- **Test:** 501 tweets (10061 tokens) (12.4%)

# References

- Di Felippo, A.; Nunes, M.G.V.; Barbosa, B. K. S. (2024) A Dependency Treebank of Tweets in Brazilian Portuguese: Syntactic Annotation Issues and Approach. In the Proceedings of the 15th Symposium in Information and Human Language Technology, 2024, Belém, v. 01. p. 01-10.
- Di Felippo, A.; Roman, N.; Pardo, T.; De Moura, L. (2023) The DANTEStocks Corpus: an analysis of the distribution of Universal Dependencies-based Part-of-Speech tags. Revista da Abralin, 22, 249-271.
- Silva, E. H.; Pardo, T.A.S.; Roman, N.; Di Felippo, A. (2021) Universal Dependencies for tweets in Brazilian Portuguese: Tokenization and Part of Speech Tagging. In the Proceedings of the 18th National Meeting on Artificial and Computational Intelligence (ENIAC), v. 01. p. 434-445. [Available here](https://sol.sbc.org.br/index.php/eniac/article/view/18273/18107)

# Changelog

* 2025-05-01 v2.16 (DANTEStocks v2.1)
  * Release of 2.1 version of DANTEStocks in Universal Dependencies, adding ExtPos features.
* 2024-11-15 v2.15 (DANTEStocks v1.0)
  * Initial release in Universal Dependencies: 1st version of DANTEStocks.
  
<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.15
License: CC BY 4.0
Includes text: yes
Parallel: no
Genre: social
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Di Felippo, Ariani; Roman, Norton Trevisan; Pardo, Thiago Alexandre Salgueiro; Barbosa, Bryan Khelven da Silva; Nunes, Maria das Graças Volpe
Contributing: elsewhere
Contact: ariani@ufscar.br,norton@usp.br,bryankhelven@ieee.org
===============================================================================
</pre>
