# Titanic EDA Project

A comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset performed in Google Colab.

## Project Overview
This project analyzes the famous Titanic dataset to understand factors that influenced passenger survival rates. The analysis includes data cleaning, feature engineering, statistical testing, and visualization.

## Dataset
- **Source**: Titanic passenger list from Kaggle
- **Rows**: 891 passengers
- **Features**: 12 original columns including survival status, class, age, gender, fare, etc.

## Analysis Steps

### 1. Data Loading & Initial Inspection
- Load dataset from public URL
- Check data dimensions and memory usage
- Examine data types and missing values

### 2. Data Cleaning & Feature Engineering
- Handle missing values in Age, Cabin, and Embarked columns
- Extract titles from passenger names
- Create new features:
  - FamilySize
  - IsAlone
  - AgeGroup
  - FareGroup
  - Title categories

### 3. Statistical Analysis
- Univariate analysis of all features
- Bivariate analysis with survival rates
- Chi-square tests for categorical variables
- T-tests for numerical variables
- Correlation analysis

### 4. Key Visualizations
- Survival rates by gender, class, and age groups
- Distribution plots for age and fare
- Correlation heatmaps
- Advanced multi-variable plots

## Key Findings

### Strongest Survival Predictors:
1. **Gender**: Women had significantly higher survival rates (74.2% vs 18.9%)
2. **Passenger Class**: 1st class passengers had 63% survival vs 24% in 3rd class
3. **Age**: Children had higher survival rates than adults
4. **Family Size**: Medium-sized families fared better than singles or large families

### Statistical Significance:
- All major factors (gender, class, age) showed statistically significant relationships with survival
- p-values < 0.001 for key categorical variables

## Requirements
- Google Colab environment
- Python libraries: pandas, numpy, matplotlib, seaborn, scipy

## Usage
Run the complete analysis by executing the single Python cell in Google Colab. The code handles all data loading, cleaning, analysis, and visualization automatically.

## Time Estimate
- Complete analysis runtime: ~1.2 hours
- Includes comprehensive statistical testing and visualization

## Further Analysis
This EDA serves as foundation for predictive modeling, feature engineering, and more advanced machine learning applications.
