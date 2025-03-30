##Kaggle House Prices Dataset Analysis
###1. Introduction

The goal of this analysis is to explore the Kaggle House Prices dataset and understand key factors influencing house prices. We examine data distributions, identify correlations, and visualize patterns to extract meaningful insights.

###2. Data Exploration & Cleaning

Dataset Overview: The dataset consists of various attributes related to house features, including square footage, quality ratings, and basement size.

Missing Values Handling: Missing values were addressed using imputation techniques like mode and median filling.

Outliers Removal: Outliers were detected using the Interquartile Range (IQR) method and removed to ensure more reliable analysis.

###3. Statistical Summary

We calculated key statistical measures for numerical columns:

Mean & Median: Provides an understanding of central tendencies in house prices and features.

Standard Deviation: Shows variability across different attributes.

Skewness: Helps detect asymmetry in data distributions.

###4. Correlation Analysis & Key Features

A heatmap was generated to identify the top 15 most correlated features with SalePrice. The most influential attributes are:

Overall Quality (OverallQual) – Strongest correlation with SalePrice.

Above Ground Living Area (GrLivArea) – Larger homes tend to have higher prices.

Total Basement Area (TotalBsmtSF) – Significant impact on pricing.

Garage Area (GarageArea) – Homes with larger garages are priced higher.

Number of Full Bathrooms (FullBath) – More bathrooms generally increase home value.

###5. Data Visualization & Findings

We used various visualization techniques to extract insights:

Histograms

SalePrice distribution shows a right-skewed pattern, meaning some houses are significantly more expensive than others.

Other features like Living Area and Basement Area also exhibit skewness.

Box Plots

SalePrice distributions were analyzed by Overall Quality and Binned Basement Area.

Higher Overall Quality scores generally correspond to higher home prices.

Basement Area shows a clear price differentiation across different size bins.

Scatter Plots (Regplots)

Created scatter plots for SalePrice vs. most correlated features.

Regression lines indicate a positive relationship between SalePrice and key attributes.

Outliers were identified and removed where necessary.

###6. Conclusions & Next Steps

Key Findings:

House prices are most strongly influenced by Overall Quality, Living Area, and Basement Area.

Some attributes like Full Bathrooms and Garage Area also impact pricing but to a lesser extent.

The dataset had several outliers that were removed using IQR method for better model performance.
