# Dissertation
## Predictive Analytics and Machine Learning Approaches to Predict Global Video Game Trends
- RACHANON CHOMPHOO
- Student ID: 22080474
- MSc. Data Science
### DATASET OVERVIEW

The dataset's information was obtained from **Kaggle**, initially scraped from Metacritic. The dataset Comprises 16,719 entries (rows) and 16 attributes (columns). It encompasses a diverse array of variables, including:

- **Descriptive attributes**: Game Name, Platform, Genre, Publisher, and Developer.
- **Temporal attribute**: Year of Release.
- **Sales data**: Regional sales (North America, Europe, Japan, Other) and Global Sales.
- **Evaluative metrics**: Critic Score, Critic Count, User Score, User Count.
- **Content rating**: ESRB Rating.

> The dataset includes video game sales data from 1980 to 2020, focusing on modern gaming eras, averaging around 2006. It covers a wide range of sales figures, with Global Sales reaching a peak of 82.53 million units, showcasing the substantial market reach of the industry.


### DATA PREPARATION

- In the dataset, a comprehensive assessment for missing values in crucial columns, namely 'Year_of_Release' and 'Genre,' data filtration was executed for 1991-2016, ensuring temporal relevance. The three processes of data ingestion known as ETL (Extract, Transform, Load) have been applied in the first file call "**VD_sales_LinearR**"

### Files

- **VD_sales_LinearR**: contain Exploratory Analysis and Linear Regression model
- **VD_sales_RidgeR**: contain Ridge Regression model
- **VD_sales_LassoR**: contain Lasso Regression model
