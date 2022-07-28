# Coherent-Voting-Network-for-PRC-prognosis
Supporting materials for the report
"Accurate prognosis for localized prostate cancer through coherent voting networks and multi-omic data",
by Marco Pellegrini. Updated as of Juny 25th 2022.


This directory  contains the train-validate-test data sets used for deriving six prognostic fingerprints in prostate cancer. 
Each file is a tab-separated csv text file. 
The first line holds TCGA-PRAD patient ID. 
The second line holds the survival class:
the year gap 2-3 corresponds to labels (below 24 months, above 36 months),
the year gap 3-4 corresponds to labels (below 36 months, above 48 months),
the year gap 4-5 corresponds to labels (below 48 months, above 60 months),

Subsequent lines hold the molecular type label and expression levels.

Train data are marked as 'train' in the file name. 
Validation data is marked as 'test1' in the file name. 
Test data is marked as 'test2' in the filename. 

The file name reports the type of TCGA-PRAD data used:
messenger RNA (mess-rna), proteomic (rppa), and microbiome (mbio).

The file name reports the year gap. 

Files for the methylation data used to obtain the 7th fingerprint (of size roughly 200MB, 300MB and 600MB) can be obtained upon request to the author.

File Table-prc-tcga-cohort-2022-07-28-medrxiv  is a csv file with additional performance  measures for the CVN-selected fingerprints.
