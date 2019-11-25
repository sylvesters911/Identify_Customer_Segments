# Identify_Customer_Segments
Look at relationships between demographics features, organize the population into clusters, and see how prevalent customers are in each of the segments obtained.

Requirement must match the Udacity Commit Message Style Guide:
1. type: subject
2. body
3. footer

##### Table of Content
1. [Installation](#Installation)
2. [Project Summary](#Project-Summary)
3. [Data](#Data)
4. [Results](#Results)
5. [Acknowledgements_and_Additional_Scripts](#Acknowledgements-and-Additional-Scripts)

## Installation
The code should run using the standard Python packages (Python versions 3.*).

This project also uses the following packages:

1. Python
2. NumPy
3. pandas
4. scikit-learn (v0.17)
5. Matplotlib
6. active_session script provided

## Project Summary
In this project, unsupervised learning techniques will be used to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data that you will use has been provided by our partners at Bertelsmann Arvato Analytics, and represents a real-life data science task.

## Data 
The data was obtained from a German company and the following files was provided:

1. Udscity_AZDIAZ_Subset.csv
2. Udacity_CUSTOMERS_Subset.csv
3. Data_Dictionary.md
4. AZDIAS_Feature_Summary.csv

All these files was read into python, and the analysis was performed.

The summary files contain the properties for each of the demographics data column. The demographics was assessed and the missing columns and rows was identified.
The columns of the features attributes summary documents the codes from the dictionary. Parsing was used to identify and clean the data. The missing or Unknown values was converted to NaN values. The Missing data from the columns for this project was removed. 

Not only was missing data was looked at, since the unsupervised learning techniques to be used will only work on data that is encoded numerically, you need to make a few encoding changes or additional assumptions. Most of the values in the dataset are encoded using numbers, not all of them represent numeric values. This is due to the re-encoding of the data.

## Results
[here](https://github.com/sylvesters911/Identify_Customer_Segments/blob/master/Identify_Customer_Segments.ipynb)

## Acknowledgements and Additional Scripts
Acknowledgements sited is Udacity and an additional script is used to keep the session active.
