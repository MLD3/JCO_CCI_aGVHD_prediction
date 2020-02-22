# JCO CCI - aGVHD_prediction

## Overview
- This is the code repository accompanying the manuscript "Predicting Acute Graft-versus-Host Disease Using Machine Learning and Lonngitudinal Vital Sign Data from Electronic Health Records".
- Authors: Shengpu Tang, Grant Chappell, Amanda Mazzoli, Muneesh Tewari, Sung Won Choi\*, and Jenna Wiens\* 

\*: senior authors of equal contribution

## Dependencies
See: requirements.txt
- python 3.7.4
- pip packages
    - numpy              1.17.3
    - pandas             0.23.4
    - tsfresh            0.13.0
    - scipy              1.3.1
    - scikit-learn       0.21.3
    - matplotlib         3.1.1
    - seaborn            0.9.0
    - tqdm               4.36.1
    - joblib             0.14.0
    
## Data
We provide anonymized patient data used in this study, including the static variables, vital sign data, and the outcome labels. A detailed description of the data can be found in the paper and the [supplemental materials](data/JCO_CCI_Supplement.pdf). 

By downloading and using the content in this repository, you agree to comply with the following guiding principles for accessing authors’ original data and code:
1. I will acknowledge the authors (Tang, et al.) of this study in future publications featuring the dataset or code that has been made available to me.
2. I may not make any attempt to identify or contact individuals whose individual-level information is contained in the dataset entrusted to me.
3. I am responsible for all misuses and inappropriate disclosures made by me or by my study team.
