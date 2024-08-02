# SPSS Correlation and Multiple Linear Regression Analysis
Estimating countries' life expectancy by considering their GDP per capita, adult mortality rate, and health expenditure per capita.

## Correlation Analysis

### Steps to Find Correlation Scores and Significance Values in SPSS

1. **Open SPSS** and load your dataset.
2. **Correlation Scores**:
    - Go to Analyze > Correlate > Bivariate....
    - Select the variables you want to correlate (e.g., `Adult Mortality` and `Life Expectancy`).
    - Ensure that the `Pearson` checkbox is selected.
    - Click `OK`.
3. **Significance Values**:
    - The output window will display the correlation coefficients (r) and the significance values (p).
    - Check the p-values to determine statistical significance. If p < 0.05, the correlation is statistically significant.
4. **Correlation Directions**:
    - Look at the sign of the correlation coefficients. A negative sign indicates a negative direction, and a positive sign indicates a positive direction.

## Multiple Linear Regression

### Steps to Perform Multiple Linear Regression in SPSS

1. **Open SPSS** and load your dataset.
2. **Multiple Linear Regression**:
    - Go to `Analyze` > `Regression` > `Linear...`.
    - Select `Life Expectancy` as the dependent variable.
    - Select `Adult Mortality`, `Percentage Expenditure`, and `GDP` as the independent variables.
    - Click `OK`.
3. **Interpret the Output**:
    - **R-Square**: In the `Model Summary` table, check the R-Square value. This represents the percentage of variance explained by the model.
    - **Significant Variables & Coefficients**:
        - In the `Coefficients` table, check the `Sig.` column to see the p-values for each independent variable.
        - Look at the `B` column under `Unstandardized Coefficients` to see the impact of each variable on the dependent variable.
        - Look at the `Beta` column under `Standardized Coefficients` to see the standardized impact.
