# BioFUnK
BioFUnK: a biomedical factuality-based uncertain knowledge graph

# Steps:
1- Download [SemMedDB](https://lhncbc.nlm.nih.gov/ii/tools/SemRep_SemMedDB_SKR/SemMedDB_download.html) and [factuality dataset](https://data.lhncbc.nlm.nih.gov/umls-restricted/ii/tools/SemRep_SemMedDB_SKR/FactualityData.zip).
2- Split the SemMedDb zipped csv files into multiple zipped csv files with equal size using the command.
3- Process the factuality dataset and train the factuality classification model.
4- Construct the different files needed for the construction of the BioFUnK KG.
5- Download the [UMLS](https://www.nlm.nih.gov/research/umls/licensedcontent/umlsknowledgesources.html) full release. Analyse and explore UMLS.
6- Extract entity and relationship abbreviations and full names.
7- Add Entity and relations names to BioFunk.
8- Add confidence scores to BioFUnK triples using the factuality classification model.
  
