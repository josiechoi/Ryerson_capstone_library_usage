# Ryerson_capstone_library_usage
Analysis of SFPL Library Usage stats for Ryerson Captone Project CKME 136
Data Source: 
https://data.sfgov.org/Culture-and-Recreation/Library-Usage/qzz6-2jup
Data Last Updated December 12, 2016 | Metadata Last Updated September 5, 2019 | Date Created December 1, 2016

## Abstract 
Using a dataset with patron records from San Francisco Public Library, this paper would explore
an question that is essential to the administrators of a public library: that is what are the demographics of
their frequent users or infrequent users? Through reviewing literatures written about this topic, this
study wish to find out what are the known about these users, and then to see if these presumptions
shall be confirmed by the findings from this dataset. An exploratory data analysis (EDA) would also be
conducted to fully understand the dataset before applying predictive data analysis.
This dataset was obtained through San Francisco Open Data project and could be found in the
Kaggle website. It contained 42000+ patron record, with fifteen variables, including age range, home
library code, year patron registered, total renewals and total checkouts in the period from 2003 to 2016.
This study planned to use total checkouts – and maybe total renewals as well - as independent variables,
turning this into a binary classification problem. Based on the number of annual total checkout (calculated by
dividing the total checkouts and/or renewals with 2016 minus year patron registered), patrons would be
divided into groups labelled as "frequent" and "infrequent" users. Then, This dataset is imbalanced and the issue of data imbalance will be addressed. I plan to use Python to apply algorithms such as random forests and KNN to this dataset. The methodology is subject to change based on the result of the EDA



