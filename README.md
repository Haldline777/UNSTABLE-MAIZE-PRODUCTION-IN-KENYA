# UNSTABLE-MAIZE-PRODUCTION-IN-KENYA
Comprehensive Report on Maize Production Analysis in Kenya

Introduction This report analyzes maize production in Kenya from 2012 to 2020. The dataset includes various counties and their maize production statistics over the years. The goal of this analysis is to identify trends, visualize key insights, and apply machine learning techniques to predict maize production levels.

Data Cleaning and Preprocessing

Loaded the dataset and removed unnecessary columns.
Cleaned column names and ensured numerical data types for analysis.
Handled missing values and formatted data for consistency.

Exploratory Data Analysis (EDA)

Histogram: Displayed the distribution of maize production for 2020.
Box Plot: Showed county-wise maize production variations in 2020.
Correlation Heatmap: Identified relationships between different production years.

Key Findings from EDA:

Significant variations exist in maize production across different counties.
Some counties exhibit high production levels, while others are consistently low.
There is a strong correlation between production levels in consecutive years.

Machine Learning Model for Prediction

Implemented a Random Forest Regressor to predict total maize production.
Data was split into training and testing sets.
Applied feature scaling for model optimization.
Evaluated model performance using Mean Absolute Error (MAE) and R² score.

Results:

MAE and R² scores provided insights into model accuracy.
Feature importance analysis identified key variables influencing production.

County-Level Analysis

Visualized county-wise maize production levels.
Identified leading and lagging counties in maize production.

Conclusion and Recommendations

Counties with consistently low production may require improved agricultural support.
Future models can incorporate additional factors such as weather conditions and soil fertility.
Policy interventions should focus on optimizing resources for underperforming counties.

This analysis provides valuable insights into the stability of maize production in Kenya, highlighting key trends and areas for potential improvement.
