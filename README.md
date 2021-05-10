# Chicago_Crime_Analytic

* Perform data exploratory on the features in the data
* Perform data cleaning on the dataset 

## Code and Resources Used

**Python Version:** 3.7 <br>
**Packages:** numpy, pandas, seaborn, matplotlib, sklearn <br>
**IDE:** Google Colab <br> 
**Dataset:** https://www.kaggle.com/currie32/crimes-in-chicago

## Data Gathering

The dataset used in this project can be downloaded from Kaggle (link as shown above). It is about incidents of crime reported in the City of Chicago from 2012 to early of 2017. The data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. There are in total 32 features as shown follows: <br>
* Date: Date of when the incident occurred.
* Primary Type: Primary description on the crime occurred.
* Location Description: Location description on where the crime occurred.
* Arrest: Indicates if an arrest has made.
* Year: Year of the incident occurred.

## Data Cleaning

This dataset consists of 1456714 entries. The following feature is with null value.

* Location Description: 1658 null values

As the number of null value is small compared to the total entries, it has decided that the entries with null values are dropped. 

## EDA

To understand the patterns and values of the data by using different types of visualizations. <br>

