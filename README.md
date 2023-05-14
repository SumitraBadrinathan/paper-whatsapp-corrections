# paper-whatsapp-corrections

## Overview
These code and data files replicate the results in "I Don’t Think That’s True, Bro! Social Corrections of Misinformation in India" by Sumitra Badrinathan and Simon Chauchard (2023). The conditonally accepted version of the manuscript can be found [here.](https://doi.org/10.1177/19401612231158770)


## Description of Files

The following files are contained in the whatsapp-corrections zip file

1. CSV dataset (ijpp-data.csv)
2. Replication R files: contains 11 R files in total. To replicate tables and figures in the main manuscript and appendix, run **main_manuscript-IJPP.R** and **appendix-IJPP.R**, respectively. These scripts begin by running the other files in order: loaddata.R, then Claim1 through Claim9. Claim1 through Claim9 contain code required to clean the original csv file, create necessary variables and generate a dataframe corresponding to each of the 9 claims in the experiment. If these files have already been run, you do not need to run them again.

Instrument for the survey (with numerical codes for response options) is available in this repository at Instrument-with-numerical-codes.pdf and Analysis-guide.xlsx provides a guide for the cleaning and variable constructions include in the code


## Replication Code and Data

To download the data needed to replicate this paper in zipped format, please click [here](<https://github.com/SumitraBadrinathan/paper-whatsapp-corrections/blob/main/whatsapp-corrections.zip> "Optional title").
