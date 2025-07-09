# Is Uber as Substitute or Complement for Public Transit：A Machine Learning Approach
**Code Author: Shuhan Yang**
## Project Overview
This project investigates whether Uber services act as a substitute or complement to public transit systems across different metropolitan areas. Using advanced machine learning techniques and panel data analysis, we estimate the causal effect of Uber's presence on public transit ridership.

*Key Finding: Uber demonstrates a statistically significant 4.28% increase in public transit ridership, suggesting a complementary rather than substitutive relationship.*
## Data
- Dataset Size: 76,000+ panel observations
- Coverage: Multiple Metropolitan Statistical Areas (MSAs)
- Time Period: Multi-year panel data
- Key Variables: Transit ridership, Uber market presence, demographic controls, economic indicators
## Methodology
### Core Approach
- **Double Machine Learning (DML)**: Applied to estimate causal effects while controlling for high-dimensional confounders
- **Panel Data Analysis**: Exploited temporal and cross-sectional variation
- **Robustness Check**: Multiple model specifications and sample restrictions
### Machine Learning Models Implemented
- Lasso Regression: For feature selection and regularization
- Random Forest: For non-linear pattern detection
- Cross-Validation: For model selection and hyperparameter tuning

## Key Features
- **Advanced Econometric Methods**: Double machine learning implementation for causal inference
- **Comprehensive Robustness Checks**: Multiple model specifications and sample restrictions
- **Heterogeneity Analysis**: Treatment effect variation by agency and MSA characteristics
- **Scalable Data Processing**: Efficient handling of 76,000+ observations
- **Statistical Validation**: Rigorous testing of model assumptions and results

## Core Analysis Pipeline
1. Data Preprocessing: Panel data cleaning and variable construction
2. Feature Engineering: Creation of interaction terms and control variables
3. Model Training: Implementation of ML algorithms with cross-validation
4. Causal Estimation: Double machine learning for treatment effect estimation
5. Robustness Testing: Multiple specifications and sample restrictions
6. Heterogeneity Analysis: Subgroup analysis by MSA characteristics

