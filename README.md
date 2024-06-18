# MACHINE LEARNING project: CLUSTERING, CLASSIFICATION, REGRESSION on codone usage frequency datasets


## Background
This project was developed as part of the Machine learning course within the Master's degree in Bioinformatics for Computational Genomics.

## Authors
This project was developed by [Elena Sasso](https://github.com/elenasasso) and [Marco Cominelli](https://github.com/marco-cominelli01).


## Project Overview

The current project focuses on predicting taxonomic identity and genetic composition based on codon usage bias levels. 
The dataset, sourced from Khomtchouk's 2020 study, comprises data from 13028 organisms classified by species and DNA type. 
Each sample is characterized by 67 attributes, including species name, species ID, total number of codons, and individual codon frequencies. 
The dataset is divided into training and test sets, with the test set missing the AGA codon frequency.

The project involves analyzing the codon usage patterns to classify organisms into their respective taxonomic groups and DNA types. 
This includes visualizing the data, identifying correlations between codon frequencies and target classes, and using clustering techniques 
to uncover patterns that differentiate the classes. 
Additionally, classification models are developed and evaluated to accurately predict the taxonomic classes based on codon usage. 
Furthermore, regression models are employed to impute the missing AGA codon frequency in the test set, with the goal of improving 
classification performance by incorporating the predicted values.


## How to Use This Repository
If you're interested in running the analysis yourself, please see the [homework.py](VarCall_pipeline.sh) script.


## Contact
For any additional questions or feedback, please contact [Marco Cominelli](mailto:cominellimarco8@gmail.com) and [Elena Sasso](mailto:elenasasso01@gmail.com).

