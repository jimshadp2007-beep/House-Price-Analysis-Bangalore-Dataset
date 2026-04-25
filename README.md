# House-Price-Analysis-Bangalore-Dataset



This project analyzes the Bangalore house price dataset with a focus on price per square foot. The objective is to perform exploratory data analysis (EDA), detect and handle outliers using multiple statistical methods, assess data distribution, and study relationships between variables.

Dataset

The dataset used in this project contains housing information such as price, area, number of bedrooms, bathrooms, and other relevant features.

Dataset link:
https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view?usp=sharing

Objectives
Perform basic Exploratory Data Analysis (EDA)
Detect and remove outliers using:
Mean and Standard Deviation
Percentile Method
Interquartile Range (IQR)
Z-Score Method
Visualize outliers using box plots and determine the best method
Analyze distribution using histogram and apply transformations if required
Compute correlation and visualize using a heatmap
Analyze relationships between variables using scatter plots
Tools and Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Steps Performed
1. Exploratory Data Analysis
Loaded the dataset and inspected its structure
Checked for missing values and data types
Generated summary statistics
Created a new feature: price per square foot
2. Outlier Detection and Removal

The following methods were used:

a) Mean and Standard Deviation
Defined acceptable range as mean ± 3 standard deviations
Removed values outside this range
b) Percentile Method
Removed values below 5th percentile and above 95th percentile
c) Interquartile Range (IQR)
Calculated Q1 and Q3
Removed values outside the range:
Q1 − 1.5 × IQR to Q3 + 1.5 × IQR
d) Z-Score Method
Computed z-scores for the feature
Removed values with z-score greater than 3 or less than -3
3. Box Plot Analysis
Box plots were used to visualize outliers before and after removal
The IQR method was found to be the most effective as it is robust to skewed data
4. Distribution Analysis and Transformation
Histogram plots were used to examine distribution
Calculated skewness and kurtosis
Observed right-skewed distribution
Applied log transformation to normalize the data
Post-transformation distribution showed improved symmetry
5. Correlation Analysis
Computed correlation matrix for numerical features
Visualized relationships using a heatmap
Identified key variables influencing house price
6. Scatter Plot Analysis
Plotted relationships between:
Price and total square feet
Price and number of bathrooms
Observed positive correlations between area and price
Results and Insights
The dataset contained significant outliers, especially in price per square foot
The IQR method performed best for outlier removal due to robustness
The data was initially skewed and improved after log transformation
Strong correlation observed between price and total square footage
Visualization techniques helped in understanding patterns and relationships
Conclusion

This analysis demonstrates the importance of handling outliers and transforming skewed data in real-world datasets. Proper preprocessing improves data quality and leads to better insights and model performance.

Submission Details
All tasks were completed as per the assignment requirements
Code implementation includes EDA, outlier handling, visualization, and correlation analysis
Visualizations support all conclusions drawn
