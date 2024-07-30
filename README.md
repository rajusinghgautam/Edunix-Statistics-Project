# Edunix-Statistics-Project

# Boston Housing Data Analysis

## Project Overview
- Analyzed the Boston housing dataset to understand housing characteristics.
- Included variables such as crime rates, property taxes, and housing values.
- Conducted visualizations and statistical tests for insights.

## Key Tasks
- **Data Exploration**:
  - Loaded and explored the dataset to understand its structure.
- **Visualizations**:
  - Boxplot: Distribution of median home values (`MEDV`) by home age groups.
  - Histogram: Distribution of the Charles River variable (`CHAS`).
  - Scatter Plot: Relationship between Nitric Oxide concentrations (`NOX`) and non-retail business acres (`INDUS`).
  - Histogram: Distribution of pupil-teacher ratio (`PTRATIO`).
- **Statistical Analysis**:
  - Pearson Correlation Coefficient: Measured the linear relationship between `NOX` and `INDUS`.

## Challenges and Solutions
- **Data Discretization**:
  - **Challenge**: Converting continuous variables into categories.
  - **Solution**: Used `pd.cut()` to create meaningful age groups.
- **Correlation Interpretation**:
  - **Challenge**: Assessing relationships from scatter plots.
  - **Solution**: Computed Pearson correlation coefficient for a quantitative measure.
- **Visualization Issues**:
  - **Challenge**: Ensuring clarity and informativeness of visualizations.
  - **Solution**: Used appropriate plot types and customized labels and titles.

## Conclusion
- Provided insights into the Boston housing data, highlighting variable relationships and patterns.
- Demonstrated effective use of visual and statistical methods for data analysis.
