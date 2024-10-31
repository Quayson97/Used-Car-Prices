## Used-Car-Prices Data set
This data set is from the IBM Data Science course on Coursera                                                                                                                                                                                                                                             
url = https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/Data%20files/auto.csv 

### Objective
The objective of this project is to apply data-cleaning techniques to the dataset, ensuring it is prepared for comprehensive exploratory data analysis. 

### Data Cleaning Techniques
1. **Handled Missing Values:** Imputed missing values using the mean for numerical columns and the mode for categorical columns.
2. **Corrected Data Formatting Issues:** Corrected the data type of some columns.
3. **Standardized the Data:** Standardized the 'fuel consumption' columns from mpg to L/100km
4. **Normalized the Data:** Used min-max scaling to normalize the "length", "width" and "height" columns.
5. **Created Bins on Certain Columns:** Binned the `horsepower` column to analyze different car prices with "high-horsepower", "medium-horsepower", and "low-horsepower".
