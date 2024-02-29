# Terro-Real-Estate-Agency
Welcome to the Terro's Real Estate Agency Data Analysis Project! This project involves analyzing a dataset of 506 houses in Boston to understand the relevance of various parameters collected by the agency in relation to the value of the houses (Avg_Price).

Project Overview

The task is to analyze the dataset to understand the extent and magnitude of each variable relative to the house's value. The project involves several steps, including generating summary statistics, plotting histograms, computing covariance and correlation matrices, building regression models, and evaluating model performance.

Project Deliverables:

1] Summary Statistics: 
Generated summary statistics for each variable in theh dataset
Observation: If we look at the “Distance” variable, we can see that the maximum distance is 24 and the mode is 24. According to this, most houses are located away from the highway.   
With the tax range of 524, the average tax paid is 408.2 
From the skewness of variables, we can say that the dataset is highly skewed.  
If we take the “Age” into consideration, we observe that maximum age is 100 and mode age is 
100 too. This indicates that most of the houses are of age 100 and above 

2. Histogram of Avg_Price Variable: Majority of the houses lie in the range $21,000 to $25,000 
Least number of hiuses range from $37,000 to $41,000 and from $45,000 to $49,000 

3. Covariance Matrix:
• CRIME_RATE has a relatively high correlation with AGE, INDUS, and LSTAT, 
indicating that these variables frequently move together. This shows that places with 
greater crime rates may also have older homes, more industrial land, and a higher 
proportion of low-income occupants. 

• Strong correlation between TAX and INDUS shows that places with more industrial land 
typically have higher real estate taxes. 

• DISTANCE has a strong negative covariance with AVG_ROOM, indicating that houses 
closer to certain amenities tend to have more rooms. 

• LSTAT has a strong negative covariance with AVG_PRICE, suggesting that areas with a 
higher percentage of lower-income residents tend to have lower housing prices. 

• Strong correlation between AVG_PRICE and TAX indicates that average home prices 
are generally higher in locations with higher property taxes. 

• NOX has a strong correlation with AGE, INDUS, and DISTANCE, indicating that 
locations with greater nitrogen oxide emissions are more likely to have older homes, 
more industrial land, and be farther from certain amenities.   

