```
Module6_claims/clean/example_2/
    STONYBRK_20240531_HEADER.csv
    STONYBRK_20240531_LINE.csv
    STONYBRK_20240531_CODE.csv
```


Link to  corresponding  corresponding assignment: https://github.com/hantswilliams/HHA-507-2025/blob/main/assignments/assignment5_files/assignment_claims.md

Link to notebook: https://colab.research.google.com/drive/1bc07S6nF2jui1kBjiHKA0ofxD-CMeeAH?usp=sharing


## Link to notebook: https://colab.research.google.com/drive/1bc07S6nF2jui1kBjiHKA0ofxD-CMeeAH?usp=sharing


## Brief project description

Primary goal of this project was to explore and assess csv files to create an analysis of billing patterns. 

## Data source information
Primary goal of this project was to explore and assess csv files to create an analysis of billing patterns. 

## Data source information

ICD Code resource: https://www.icd10data.com/ICD10CM/Codes




## How to run the notebook: 
You can proceed to run the note book either code by code or all at once. 

#### Code by code: 

1. Load the corresponding csv file based on the section and question required.

2. Click the run button on the left hand side to the corresponding code. 


#### All at once:

1. Load all csv files into folder (please note: storage of files is temporary, please save files in local repository or storage on device).

2. On the top left section proceed to run all code within notebook. 

## Summary of key findings (3-5 bullet points)
ICD Code resource: https://www.icd10data.com/ICD10CM/Codes




## How to run the notebook: 
You can proceed to run the note book either code by code or all at once. 

#### Code by code: 

1. Load the corresponding csv file based on the section and question required.

2. Click the run button on the left hand side to the corresponding code. 


#### All at once:

1. Load all csv files into folder (please note: storage of files is temporary, please save files in local repository or storage on device).

2. On the top left section proceed to run all code within notebook. 

## Summary of key findings (3-5 bullet points)

1. The most frequent ICD-10 code "Acute respiratory Failure with hypoxia" corresponds with the most frequent HCPCS Code "Critical care, first hour". 

2. "Inpatient" has the highest percentage of claims total. This could be due to increased cost requirement for inpatient care compared to ambulatory services. However, Emergency care has a lower claim total. Inpatient claim total could include multiple services such as Internal medicine to more costly services such as Intensive care or Surgical services.   

3. Medicare is one of the top payers present within the csv files and covers for multiple services and not just inpatient. A significant portion of patients are reliant on Medicare to cover to healthcare costs. As seen with question 9, Medicare is the most prevalent payer individually compared to other payers. However, when compared to other payers combined, medicare covers about 45% of patients that recieve Critical Care within first hour. 



### Required libraries

```bash 
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```
