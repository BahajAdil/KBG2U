# BioFUnK
BioFUnK: a biomedical factuality-based uncertain knowledge graph

# Description
This repository contains the source code used to construct BioFunK. BioFunk is a general purpuse biomedical uncertain knowledge graph that is based on the SemMedDb medical database. bioFUnK takes advantage from the richness of SemMedDb and adds an uncertainty elements to it. Specifally, for each SemMedDB fact $f=(head, rel, tail)$ a score $s \in [0,1]$ is added. This score is based on the support set of $f$, that is the set of sentences where the triple occurs. We extract the sentence factuality using a factuality classification model. These factuality classes are then transformed to values in $[0,1]$ and aggregated to get the score of the fact.
</br>
</br>
![alt text](https://github.com/team611/biofunk/blob/main/assets/completSysFig-1.png?raw=true)

# Steps:
0. Register for a UMLS account.
1. Download [SemMedDB](https://lhncbc.nlm.nih.gov/ii/tools/SemRep_SemMedDB_SKR/SemMedDB_download.html) and [factuality dataset](https://data.lhncbc.nlm.nih.gov/umls-restricted/ii/tools/SemRep_SemMedDB_SKR/FactualityData.zip).
2. Split the SemMedDb zipped csv files into multiple zipped csv files with equal size using the command.
3. Process the factuality dataset and train the factuality classification model.
4. Construct the different files needed for the construction of the BioFUnK KG.
5. Download the [UMLS](https://www.nlm.nih.gov/research/umls/licensedcontent/umlsknowledgesources.html) full release. Analyse and explore UMLS.
6. Extract entity and relationship abbreviations and full names.
7. Add Entity and relations names to BioFunk.
8. Add confidence scores to BioFUnK triples using the factuality classification model.
  
