# Replication files de Vos en Verberne 2021

These are the replication files of a paper I published together with Suzan Verberne.

Find the paper on arxiv: https://arxiv.org/pdf/2109.12911.pdf

Originally published at the 1st Workshop on Computational Linguistics for Political Text Analysis (CPSS-2021) Düsseldorf. Find the full proceedings of the workshop at: https://gscl.org/media/pages/arbeitskreise/cpss/cpss-2021/workshop-proceedings/352683648-1631172151/cpss2021-proceedings.pdf



This Repository contains 4 subfolders: 

1. **Data**: this folder contains all data that is needed to replicate the study. These are 2 .csv files (can be opened with among others Microsoft Excel). coded-tweet-data.csv contains the labeled tweets that serve as training set and test set to the machine learning model. agency_tweets_database.csv contains unlabeled tweets. N.B. Both files are identical to the files appended to Anastasopoulos and Whitford (2019).
2. **rmd_files**: This folder contains the raw R-markdown files. These files can be opened and run with R-studio. Executing these files will replicate the entire study. If the data-files are kept in their folder after extraction of the zip, the script is able to find them without any alterations. Note that for the script to run properly, some extra R-libraries need to be installed, preferably the versions indicated in the R-markdown files.
3. html_files: This folder contains the compiled rmd-files (including output) in HTML-format. These files can be opened with any web browser (firefox or google chrome are recommended.). Use these if you
4. Figures: this folder contains all the figures created with the scripts. When the rmd-files are run after extraction of the zip-file, all figures will be placed in this folder. **NOTE, if you re-run the rmd files, the original figures might get replaced.**
