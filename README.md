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

#### Number of Crime Reported in Chicago: 2012 - 2017 
![](/images/overall_crime_20122017.png)
<br>Based on the graph, it can be seen that the trend for the crimes reported in chicago is about the same for each year, which is increases at the beginning of the year and
decreases from the middle of the year until the end of the year. 

#### Crime Reported in Chicago (Rolling Sum): 2012 - 2017 
![](/images/roll_sum_2012-2017.png)
<br> By using the rolling sum with 365 days, it can be seen that the crime reported is reducing across the year. 

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)

#### Heatmap of correlation between the features 
![](/images/HRC_Corr.png)


