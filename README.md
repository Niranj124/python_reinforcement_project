# python_reinforcement_project
# PROJECT WORKFLOW:
## Data Collection & Loading
•	Loaded the dataset using Python libraries such as Pandas and NumPy.
##  Data Cleaning
•	Filled missing values using statistical imputation.
•	Treated outliers using the IQR method.
•	Corrected unrealistic and inconsistent entries.
## 	Feature Engineering
•	Created derived metrics:
• age_of_Property = 2014 - yr_built
• price_per_sqft = price / sqft_living
• df['is_renovated'] = df['yr_renovated'].apply(lambda x: 1 if x > 0 else 0)
## 	Statistical Analysis
•	Performed descriptive stats,one way t-tests, two way t-test,one way Anova-test and chi-square tests to evaluate significance.
##  Exploratory Data Analysis (EDA)
•	Exploratory Data Analysis (EDA) included univariate (histograms, boxplots), bivariate (scatter plots, correlation heatmaps), and multivariate analysis (pairplots) to explore distributions and relationships between housing features. 
## 	Insight Extraction
•	Summarized findings to guide data-driven decision-making.
