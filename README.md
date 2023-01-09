# Coherent-Voting-Network-for-PRC-prognosis
Supporting materials for the report:

Marco Pellegrini 
Accurate prognosis for localized prostate cancer through coherent voting networks and multi-omic data  
medRxiv 2022.07.28.22278156; doi: https://doi.org/10.1101/2022.07.28.22278156 (July 2022)    https://www.medrxiv.org/content/10.1101/2022.07.28.22278156v1

Updated as of July 31st 2022.


This directory  contains the train-validate-test data sets used for deriving six prognostic fingerprints in prostate cancer and the mixed clinical and genomic fingerprint. 
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

File Table-prc-tcga-cohort-2022-07-27  is a csv file with additional performance  measures for the CVN-selected fingerprints.
File Table-ind-cohorts-bootstrap-factor3-2022-07-31-reduced is a csv file with additional performance measures for bootstrap evaluation of fingerprints on independent cohorts. 
File Table-mixed-clinical-genomic-2023-01-09-reduced.csv is a comma-separated csv file holding performance measures for the mixed clinical and genomic fingerprint fp160.

