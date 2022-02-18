# Capstone-NYC-Rental-Price

### Goal: 
This project aims at helping individuals find a new home in New York City based on their own criteria! We will examine the extrinsic factors of each Neighborhood, analyze which apartments are over market values; and narrow down this choice to a few select listings so that apartment hunting becomes a less daunting task!  

### Exploring the DataSets; 
In this project we utilize two datasets:
1. New York City Rent Prices for 2020 Dataset
2. Neighborhood Extrinsic Factors - Housing Authority Dataset

### Zillow – New York City Rent Prices for 2020 Dataset 
#### Data Wrangling
- 7000 unique listings for apartments in New York City in 2020, with over 20 features
- However, to ensure that all this data is accurate, we had to filter the data, by removing listings not in NYC, or listings whose rent cost were astronomical. After filtering the data, we removed 20% of the listings.
- Utilized Google Maps API to view location of all filtered data

#### Exploratory Data Analysis
- Utilized boxplots, scatter plots and bar plots to explore and analyze the data. 

### Neighborhood Extrinsic Factors – NYC Housing Authority
#### Data Wrangling
- This dataset includes the 55 neighborhoods in NYC, and 33 features. These features are useful for comparing extrinsic factors, including Number of Housing Units, Average Price, Locations of Public Transportation

#### Exploratory Data Analysis
- Utilized correlation matrix to see how the 33 extrinsic features are correlated. 

### Principal Component Analysis
Our Dataset has more than 40 features, we will apply PCA to visualize this high dimensional data. By imposing the different Boroughs and Rent Prices on our PCA visualization, we can see how they tend to cluster.

### Machine Learning Models
- Applied Hyperparameter Tuning and Feature Engineering to test how well Linear Regression, Ridge Regression and Random Forest Regressor Perform in analyzing the Data. 
