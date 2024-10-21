# Bank Loan Case Study

Using Exploratory Data Analysis (EDA) to find key insights regarding bank loan data.

## Project Description

This project focuses on analyzing patterns and trends in loan applications to identify factors that may lead to loan defaults. The company specializes in lending loans to urban customers and faces challenges in ensuring that loans are not approved for customers who might have difficulty paying their installments. Through EDA, the goal is to provide actionable insights and support decision-making for loan approvals.

## Approach

The approach involved applying key EDA techniques to:

1. **Identify missing data**: Handle missing data through imputation or flagging.
2. **Detect outliers**: Investigate outliers to assess their impact.
3. **Analyze data imbalance**: Evaluate target variable distribution.
4. **Univariate, segmented univariate, and bivariate analysis**: Explore individual and paired variable relationships.
5. **Identify top correlations**: Rank correlations between variables and the target.

## Tech-Stack Used

- **Microsoft Excel 2022** was used for the analysis.
- Functions like `COUNT`, `COUNTBLANK`, `AVERAGE`, `MEDIAN`, `CORREL` were employed.
- Data visualization included histograms, pie charts, box plots, and scatter plots.

## Key Tasks

### Task A: Identify Missing Data
- Handled missing data using mean, median, or mode imputation.
- Columns with more than 40% missing values were removed.

### Task B: Identify Outliers
- Detected outliers using the Interquartile Range (IQR) method.
- Outliers were removed to avoid skewed results.
  - Incomes above 10,000,000
  - Credited Amounts above 3,000,000
  - Annuity Amounts above 1,500,000
  - Goods Prices above 2,500,000

### Task C: Analyze Data Imbalance
- Investigated imbalance in loan approval using the `COUNTIF()` function.
- Visualized the class distribution using pie and bar charts.

![Data Imbalance Chart](path_to_your_image/data_imbalance_chart.png)

### Task D: Univariate, Segmented Univariate, and Bivariate Analysis
- Analyzed variable distributions and relationships using pivot tables, filters, and descriptive statistics.
- Identified trends and insights into loan defaults.

![Bivariate Analysis Chart](path_to_your_image/bivariate_analysis_chart.png)

### Task E: Identify Top Correlations
- Calculated correlations using Excel’s `CORREL()` function.
- Visualized results with heatmaps and correlation matrices.

![Correlation Heatmap](path_to_your_image/correlation_heatmap.png)

## Key Insights

- Ages between 40-50 were most likely to use credit.
- Females had a slightly higher percentage of non-defaulters.
- Higher education levels were linked to better annual income.

## Result

The project successfully identified key factors contributing to loan default risk. Detailed EDA uncovered trends in customer behavior, aiding in more accurate loan approval decisions and helping mitigate financial risks.

## Conclusion

This analysis provided a deeper understanding of how customer attributes, such as income level and loan amount, impact loan default risk. These insights will help the company approve capable applicants and mitigate financial losses.

