# Employee Attrition
### Introduction

Employee loyalty is becoming a thing of the past and workers are realizing that they must job-hop for career growth and higher salaries. 
Employers are finding that their attrition rates are now higher than yesteryear and must implement strategic ways to retain skilled workers.


## Business Problem

The CHRO (Chief Human Resources Officer) has noticed an uptick in attrition and believes the majority of workers 
exiting the company are younger employees while older workers are staying put, however, this is just a gut feeling, 
and she wants strong evidence to back up her assumption. As the HR analyst, I'm tasked with determining whether the CHRO's assertion is accurate.


## Solution Brainstorming

I will use an augmented HR dataset from Kaggle provided by a real IBM data scientist to solve this problem. Firstly, 
I will get acquainted with the data and then apply inferential statistics to determine if what I'm observing from the data is statistically significant.

The dataset can be found [** here **](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

My full R script can be found [** here **](github.com/ashurland/hello-world/blob/master/HR_Project.R)


## Data Profiling

The dataset has 1470  observations and 35 fields with all categorical variables represented as character datatypes. 
The character datatype will not be useful when calling the summary function in R and therefore has to be changed to get meaningful output. 
Likewise, the variable "ï..Age"  has to be renamed to "Age" for clarity and the dataset contains no missing data.
Images 1 and 2 illustrate the aforementioned information.
