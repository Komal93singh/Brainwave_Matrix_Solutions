# METRO SYSTEMS WORLDWIDE


## Problem Statement : 
Metro Cities Data : The subway system or metro trains have been benefitting the modern civilizations commute hassle-free from manay years. And each year new additions are made to the already existing rail network serving millions of people everyday.

Your job is to identify the underlying patterns by performing EDA using python on the metro data and gather useful insights that will be beneficial for anyone that wishes to use the same data for further analysis.


## Description : 
This list of metro systems includes electric rapid transit train systems from throughout the world. Metro systems are known as subways, U-Bahns, or undergrounds in different regions of the world. As of May 2023, 194 cities in 62 nations had a metro system.

## Dataset Information :
Feature | Description 'city' | Name of the city 'country' | Name of the country 'name' | Name of the Metro 'year' | Year it was built 'year_last_expansion' | Year when the last expansion happened 'stations' | Number of stations 'length_km' | The Length of the network in KM 'annual_ridership_mill' | Annual riders in millions 'region' | The region it is located in

## Project Structure :
1. Data Preprocessing: This section involves cleaning the dataset, handling missing values, and converting categorical variables into numerical format.

2. Exploratory Data Analysis (EDA): Here, we explore the dataset to gain insights into the relationships between different features. Visualizations such as bar plots, and correlation matrices are used for analysis.

## Observation :
- The strength of the relationship between the two variables is weak. This means that changes in one variable are not strongly associated with changes in the other variable.

- Positive Relationship: The positive sign indicates that as one variable increases, the other variable tends to increase as well, but the relationship is not strong.

- Limited Predictive Power: Since the correlation coefficient is low, it suggests that using one variable to predict the other may not be very accurate. In other words, knowing the value of one variable provides limited information about the value of the other variable.

- Overall, while a correlation coefficient of 0.44 indicates some degree of association between the variables

## Result :
- Positive correlations have been observed between
1. year and year_last_expansion
2. year_last_expansion and stations
3. station and length_km
4. length_km and annual_ridership_mill
   
- Here, there is no negative correlation have been observed.

## Conclusion :
- Region wise anlayis:
  1. In africa region , annual ridership million is 1363.86
  2. In latin america region , annual ridership million is 4,046.1
  3. In Asia region , annual ridership million is 39,018.74
        - It is highest among all region.
  4. In Australia region , annual ridership million is 16.3
        - It is lowest among all region.
        - Less number of station among all region.
  5. In Europe region , annual ridership million is 11,961.03
        - It is 2nd highest among all region.
  6. In North America region , annual ridership million is 2,876.7
        - It is 3rd highest among all region.
  7. correlation coefficient of 0.44
     
Through this project, I have successfully analyzed the METRO SYSTEMS WORLDWIDE dataset. This project serves as a demonstration of data preprocessing, exploratory data analysis and correlation.

## Contact Information : 
For any inquiries or feedback regarding this project, please contact:

   - LinkedIn: https://www.linkedin.com/in/komal-b61580158/
   - Email: komal93singh@gmail.com
