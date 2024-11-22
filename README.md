# Correlation Analysis of Happiness and Income Data

This project analyzes the correlation between economic and happiness-related factors using a dataset of global countries. It explores statistical relationships between variables such as GDP, happiness scores, income inequality, and satisfaction levels.

## Dataset

The dataset used in this analysis includes the following fields:

- **country**: Name of the country
- **adjusted_satisfaction**: Adjusted satisfaction level
- **avg_satisfaction**: Average satisfaction level
- **std_satisfaction**: Standard deviation of satisfaction
- **avg_income**: Average income
- **median_income**: Median income
- **income_inequality**: Measure of income inequality
- **region**: Geographical region
- **happyScore**: Happiness score
- **GDP**: Gross Domestic Product
- **country.1**: Duplicate of the country column

**Dataset Source:** The dataset is available [here](https://raw.githubusercontent.com/emilyyyyyleeeee/ITP487_Correlation_Analysis_IC/main/happyscore_income.csv).

## Methods

### Data Cleaning

1. Extracted relevant columns for correlation analysis:
   - `GDP` and `happyScore`
   - `income_inequality` and `std_satisfaction`
2. Removed duplicates and handled missing data.

### Correlation Analysis

The correlation between variables was computed using three methods:
- **Pearson**: Measures linear correlation.
- **Kendall**: Measures ordinal correlation.
- **Spearman**: Measures rank correlation.

#### Results:

1. **GDP and Happiness Score:**
   - Pearson Correlation: 0.79
   - Kendall Correlation: 0.60
   - Spearman Correlation: 0.79

2. **Income Inequality and Standard Deviation of Satisfaction:**
   - Pearson Correlation: 0.22

## Project Structure

. ├── Correlation-Analysis.ipynb # Jupyter Notebook for analysis ├── happyscore_income.csv # Dataset └── README.md # Project documentation

## Insights

- There is a strong positive correlation between GDP and happiness scores across countries.
- Income inequality has a weaker correlation with standard deviation in satisfaction levels.
