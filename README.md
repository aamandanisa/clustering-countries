# **Clustering Countries**

# Introduction

- HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.
- After the recent funding programmes, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid.
![image](https://user-images.githubusercontent.com/96335700/150803682-c6644153-e7f5-4586-b49f-f369407d1f82.png)

  
# Objectives

- Data inspection and EDA tasks suitable for this dataset - data cleaning, univariate analysis, bivariate analysis etc.
- Outlier Analysis: You must perform the Outlier Analysis on the dataset. However, you do have the flexibility of not removing the outliers if it suits the business needs or a lot of countries are getting removed. Hence, all you need to do is find the outliers in the dataset, and then choose whether to keep them or remove them depending on the results you get.
- Create model using both K-means and Hierarchical clustering(both single and complete linkage) on this dataset to create the clusters.
- Analyse the clusters and identify the ones which are in dire need of aid. You can analyse the clusters by comparing how these three variables - [gdpp, child_mort and income] vary for each cluster of countries to recognise and differentiate the clusters of developed countries from the clusters of under-developed countries.
- Perform visualisations on the clusters that have been formed using the features selected for building the clustering model


# Data Understanding

- country : Name of the country
- child_mort : Death of children under 5 years of age per 1000 live births
- exports : Exports of goods and services per capita. Given as %age of the GDP per capita
- health : Total health spending per capita. Given as %age of GDP per capita
- imports : Imports of goods and services per capita. Given as %age of the GDP per capita
- income : Net income per person
- inflation : The measurement of the annual growth rate of the Total GDP
- life_expec : The average number of years a new born child would live if the current mortality patterns are to remain the same
- total_fer : The number of children that would be born to each woman if the current age-fertility rates remain the same
- gdpp : The GDP per capita. Calculated as the Total GDP divided by the total population




# Data Cleansing 

- The dataset contains 167 rows and 10 columns. Out of these 10 columns, 9 are integer type and only 1 object/categorical column is present which is the name of the country.
- There are no Null or Nan values.
- Check the duplicates data
- ![image](https://user-images.githubusercontent.com/96335700/150805367-3e620840-d8e4-4a8b-a18f-5c180cf27c66.png)


# Exploratory Data Analysis

