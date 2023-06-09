Crime Analysis in US Communities
Introduction
Crimes are a pressing issue in various communities across the USA. In this project, we will explore a dataset called "Communities and Crime Un-normalized Data Set" to identify patterns and gain insights into the crime rates in different communities. By analyzing the data, we aim to provide recommendations to the law enforcement system, enabling them to make informed decisions to control and reduce crime rates.

About the Dataset
The dataset consists of information on crimes in different communities of the USA. It includes various types of crimes, both violent and non-violent, reported in each community. The dataset comprises 147 features, with 146 independent variables and one target variable. It contains 2,215 rows of data. The dataset may have some missing values denoted by "?" symbols, and the data is somewhat unstructured. Moreover, there is no significant correlation among most of the variables.

Objectives
Using data analysis and visualizations, our objectives are as follows:

Identify the states with the highest crime rates.
Determine the age group that is more likely to commit crimes.
Explore the correlation between different types of crimes.
Suggest preventive measures to reduce crimes in the US.
Challenges
During the analysis, we encountered several challenges:

The dataset contains numerous missing values denoted by "?", which required handling.
The data was somewhat unstructured, requiring preprocessing to make it usable for analysis.
Importing an Excel file into Google Colab using Pandas presented initial difficulties, which were resolved by installing the necessary package.
The dataset includes a large number of attributes, making it difficult to explain and understand all variables.
Community names in the dataset were messy, often including additional strings such as "city" or "township."
Columns with more than 30% missing values were dropped, but it remains uncertain if those variables would have provided valuable insights.
After analyzing the data, we split it into training and testing sets and fitted models using linear and random forest regressions. Relevant metrics were calculated for evaluation.
For more detailed information and code implementation, please refer to the README file in the project's GitHub repository.
