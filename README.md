### Overview
This project aims to predict life expectancy based on key socio-economic and health-related features, helping identify areas of weakness that can be targeted to improve overall quality and longevity of life.

### Project Highlights

Data Preprocessing & Cleaning:
Conducted thorough exploratory data analysis to identify and handle anomalies. Missing values were imputed using correlation-based strategies; features with strong correlations were imputed accordingly, while others were filled using their median values.

Model Development:
Trained a Linear Regression model on the cleaned dataset, achieving an Adjusted R-squared of 83.5%, indicating a strong fit.

Feature Selection:
Employed various techniques to optimize model performance, including:

Partial F-test for assessing feature relevance, 
Mean Squared Error (MSE) analysis, 
Elimination of features causing multicollinearity
