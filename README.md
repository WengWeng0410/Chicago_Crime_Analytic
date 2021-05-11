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

#### Arrest Statistic in Chicago: 2012 - 2016 
![](/images/arrest_stat_20122016.png)
<br>Based on the graph, it can be seen that the arrest statistic is low (more than 50% of the crimes reported) across the year.

#### Top 20 Crimes Reported in Chicago: 2012 - 2017
![](/images/top20_crime_20122017.png)
<br>Based on the graph, the first 5 crimes reported the most in Chicago from 2012 to 2017 are theft, battery, criminal damage, narcotics and assault. 

#### Arrest Statistic for the Top 20 Crimes Reported in Chicago: 2012 - 2017
![](/images/top20_arres_stat_20122017.png)
<br>Based on the graph, it can be seen that the arrest statistics are poor for the crimes with high reported cases. 

#### Top 20 Locattions with the Most Crimes Reported in Chicago: 2012 - 2017
![](/images/top20_crimeloc_20122017.png)
<br>Based on the graph, it can be seen that location of Street, Residence, Apartment and Sidewalk are with high number of crimes reported.

#### Arrest Statistic on Top 20 Locattions with the Most Crimes Reported in Chicago: 2012 - 2017
![](/images/top20_arrest_crimeloc_20122017.png)
<br>It can be seen that the arrest statistics are very poor for the crimes incident occurred on Street, Residence and Apartment.

#### Montlhy Crime Reported in Chicago for the Years 2012 - 2016
![](/images/montly_crime_20122017.png)
<br>Based on the graph, it can bee seen that the crimes trent are about the same accross the years 2012 - 2016. 

#### Number of Crime Reported in Different Seasons at Chicago: 2012 - 2017
![](/images/overall_season_crime_20122017.png)
<br>Based on the graph, summer is with the highest number of crimes reported and winter is the lowest. 

#### Distribution of Crime Reported Over A Day (00:00 to 23:59) in Chicago: 2012 - 2017
![](/images/overall_hourly_crime_20122017.png)
<br>As shown from the graph, less crimes are committed at the midnight. 

#### Distribution of Top 20 Crimes in Chicago: 2012 - 2017
![](/images/individual_crime_20122017.png)
<br>Based on the graphs above, it can be seen that crimes 
