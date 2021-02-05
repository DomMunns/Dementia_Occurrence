BIO00058M-Using supervised machine learning to determine the importance of mini-mental state examination score and 
normalized whole-brain volume when predicting dementia group

Description:

Two data sets in separate sheets contained in the same excel file were imported, processed and merged into one dataframe. 
This dataframe was used to produce two LDA models one including MMSE and nWBV, and one without. These models were used to
produce LDA scatter graphs. After processing and merging of the data produced by the models a bar chart was produced to 
compare the accuracy of the models. 

Technical description:

R version 4.0.3 (2020-10-10)

Packages
- tidyverse_1.3.0
- caret_6.0-86
- readxl_1.3.1
- dplyr_1.0.3
- rmarkdown_2.6
- bookdown_0.21

Notes:

