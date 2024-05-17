# Outlier-Removal
[Dataset](https://drive.google.com/drive/folders/11Vd9c1flngkjCtnyJBET4z5421RQjA_o?usp=sharing)
# House Price Analysis

## Introduction
In this project, I performed an analysis of property prices in the city of Bangalore using the `house_price.csv` dataset. The main objective was to examine the price per square feet and detect outliers using various methods such as mean function, percentile method, interquartile range method, normal distribution, and Z-score method. Additionally, I visualized the data using box plots, histograms, correlation heatmaps, and scatter plots.

## Tasks Completed
- Loaded the dataset and examined if there are any null values.
- Detected outliers in the price per square feet column using box plots and histograms.
- Removed outliers using mean function, percentile method, interquartile range method, normal distribution, and Z-score method.
- Plotted box plots for all numerical columns to visualize outliers.
- Checked the normality of the price per square feet column using a histogram.
- Calculated the correlation between numerical columns and plotted a heatmap.
- Created scatter plots between variables to check their correlation.

# Visualizations
- Box plot of Price per Sqft
- Histogram of Price per Sqft
- Correlation Heatmap
- Pairplot of Numerical Columns

## Conclusion
***Overall, this analysis provides insights into the distribution of property prices in Bangalore and highlights the effectiveness of various outlier detection methods. The visualizations help in understanding the relationships between different numerical variables and identifying any potential patterns or trends.***




# Hypothesis Testing

## Introduction
In this project, we perform hypothesis tests to analyze claims made in two different scenarios. Hypothesis testing is a statistical method used to make inferences about population parameters based on sample data. 

## Tasks
## Task 1: Child Psychologist's Claim

- Claim: A child psychologist asserts that the average time working mothers spend talking to their children is at least 11 minutes per day.
- Sample: A random sample of 1000 working mothers was selected, revealing an average time of 11.5 minutes spent talking to children per day.
- Population Standard Deviation: Previous research suggests a population standard deviation of 2.3 minutes.
- Hypothesis Test: A hypothesis test was conducted with a significance level (alpha) of 0.05 to ascertain if there is sufficient evidence to support the psychologist's claim.
- Additional Note: Since we have a sample size of 1000, which exceeds 30, and we possess information about the sample mean, standard deviation, and aim to compare the sample mean to a 
  population value, a Z-test is appropriate.

***Result: The calculated z-score (6.88) significantly exceeds the critical value (1.645), leading to the rejection of the null hypothesis. Therefore, there is substantial evidence to conclude that working mothers spend more than 11 minutes per day talking to their children.***

## Task 2: Coffee Shop's Claim

- Claim: A coffee shop asserts that their average wait time for customers is less than 5 minutes.
- Sample: A sample of 40 customers was observed, yielding an average wait time of 4.6 minutes with a standard deviation of 0.8 minutes.
- Hypothesis Test: A hypothesis test was conducted at a significance level of 0.05 to determine if there is adequate evidence to support the coffee shop's claim.
- Additional Note: Since the sample size is small (typically <30) and the population standard deviation is unknown, a t-test is appropriate for this scenario.

***Result: The calculated t-value (-3.16) is lower than the critical t-value (-1.685), leading to the failure to accept the null hypothesis. This indicates sufficient evidence to support the claim that the average wait time for customers is less than 5 minutes at a significance level of 0.05.***

## Conclusion
Hypothesis testing allows us to evaluate claims or hypotheses about population parameters using sample data. By setting up null and alternative hypotheses and conducting appropriate tests, we can make informed decisions about the validity of these claims. The results of these tests provide valuable insights for decision-making in various fields.


# DATA PREPROCESSING

## Objective:
***This project aims to develop a reliable data preprocessing system to enhance the quality and usability of datasets for machine learning applications. By addressing issues like missing values, outliers, and inconsistent formatting, we strive to improve data integrity and analysis outcomes.***

[DATASET](https://drive.google.com/drive/folders/18rpobr58R_e8zrp26Nk1ievYmhHB7_kT?usp=sharing)

## Key Components:
- ***Data Exploration:*** Understand dataset structure, identify unique values, and perform basic statistical analysis
- ***Data Cleaning:*** Handle missing values, remove duplicates, and address outliers.
- ***Data Analysis:*** Filter and visualize data based on specific criteria.
- ***Data Encoding:*** Convert categorical variables into numerical representations.
- ***Feature Scaling:*** Standardize or normalize feature values for improved model performance.

## Next Steps:
- Explore the provided dataset and run the preprocessing script to observe its effects.
- Experiment with different preprocessing techniques to optimize data quality.
- Share feedback or suggest improvements to enhance the preprocessing system.

# Linear Regression
## Car Price Prediction with Linear Regression

[DATASET](https://drive.google.com/file/d/1aZp__A7mMpewcLwGbopkxQIKTG03vd41/view?usp=sharing)

## Introduction:

Welcome to my project on predicting car prices using linear regression! I've analyzed a dataset containing information about different cars, like horsepower, mileage, and more. Using this data, I've built a model to predict car prices based on these features.

## Objective:

The goal is to develop a model that accurately estimates car prices based on their characteristics. We'll use linear regression to understand how features influence price and create a model for reliable predictions.

### Approach:

- ***Data Exploration***: Understand the dataset's structure and relationships between features and prices.
- ***Data Preprocessing***: Handle missing values, encode categorical variables, and scale numerical features.
- ***Model Building***: Use linear regression to learn the relationship between input features and prices.
- ***Model Evaluation***: Assess the model's performance using metrics like R-squared and Mean Squared Error.
- ***Prediction***: Use the trained model to predict car prices.

## Conclusion:

This project demonstrates how linear regression can predict car prices accurately. By analyzing the dataset and building a predictive model, we gain insights into factors influencing car prices and provide a practical tool for estimating values.


# Clustering Analysis on the Iris Dataset

This project applies various clustering methods to the Iris dataset to uncover hidden patterns in the data. We use K-means clustering, Agglomerative clustering, and Hierarchical clustering, and evaluate their performance.

## Dataset

The Iris dataset contains 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. There are three species: Iris setosa, Iris versicolor, and Iris virginica.


## Clustering Techniques

***1. K-means Clustering:*** Partitions data into K clusters by minimizing the variance within each cluster.

***2. Agglomerative Clustering:*** Builds clusters hierarchically using the Ward linkage method.

***3. Hierarchical Clustering:*** Produces a dendrogram to visualize nested groupings.

### Evaluation Metric
- ***Silhouette Coefficient:*** Measures how similar a point is to its own cluster compared to other clusters. Higher values indicate better-defined clusters.
