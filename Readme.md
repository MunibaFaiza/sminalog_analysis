# SMINA Log File Analysis

## Python Script for SMINA log file analysis

### Introduction

sminalog_analysis.py script fetches all binding affinities of top poses of each ligand giving a serial number to each one of them from SMINA output log file. SMINA log file can be useful in the conditions where you need only binding affinities of the ligands regardless of their identities. One such example is the AUC-ROC analysis, calculation enrichment factor (EF) values, and so on.

### Usage:

To use this script, run the following command:

```$ python sminalog_analysis.py```

After running the above command, you will see the directory path where you have kept the file along with its name. A few seconds later, it will display "Done! The result is provided in the output.txt file". A new file will be created namely, 'output.txt', in the same directory. This file will contain the final results.

***For example,***
Say, you have docked 3000 ligands from a database and want to get the binding affinities of the top poses of each of these ligands. Then run the above command and wait for the output file.

***NOTE: This script screens for the log files containing the word 'log' in their filenames.

For more information on this script, please visit the following link:
https://bioinformaticsreview.com/20210611/sminalog_analysis-py-a-new-python-script-to-fetch-top-binding-affinities-from-smina-log-file

### How to cite:
Faiza M., Abdullah T. (2021). sminalog_analysis.py - A Python script to fetch top binding affinities from SMINA log file. 8(6):page 16-18. The article is available at https://bioinformaticsreview.com/20210611/sminalog_analysis-py-a-new-python-script-to-fetch-top-binding-affinities-from-smina-log-file
