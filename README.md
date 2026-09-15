# Capstone-Project---Financial-Advisory-Clients-Data-Analysis
A Data-Driven Analysis of Client Demographics and Financial Characteristics

Financial Advisory Clients Data Analysis

### Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

### Project Description

This project analyzes a Financial Advisory Clients dataset containing 5,000 client records and 31 original attributes. The main purpose of the project is to understand clients' demographic, financial, investment, risk, and advisory-service characteristics and generate useful business insights.

The analysis was performed using Python, Pandas, NumPy, Matplotlib, Seaborn, and Plotly in Jupyter Notebook.

### Objectives

The main objectives of this project are to:

* Understand the characteristics of financial advisory clients
* Analyze income, expenses, debt, savings, and investments
* Study client risk tolerance and financial goals
* Understand communication preferences and client satisfaction
* Identify relationships between different financial variables
* Generate meaningful business insights and recommendations

### Dataset

The dataset contains information about:

* Age and demographic details
* Employment status
* Annual income
* Monthly expenses
* Total debt
* Credit score
* Emergency fund
* Investment portfolio
* Financial goals
* Time horizon
* Risk tolerance
* Preferred communication channel
* Check-in frequency
* Advisory session duration
* Client satisfaction
* Trust in financial institutions

### Data Preprocessing

The dataset was checked and cleaned before analysis.

The preprocessing included:

* Checking missing values
* Handling missing values using mean, median, zero, and formula-based approaches where appropriate
* Checking and removing duplicate records
* Validating data types and values
* Checking invalid values
* Detecting outliers using the IQR method
* Retaining valid financial outliers when they represented realistic client behaviour
* Feature Engineering

Several new variables were created to improve the analysis, including:

* Monthly Income
* Disposable Income
* Expense-Income Ratio
* Emergency Fund Amount
* Age Group
* Risk Category
* Total Number of Topics Discussed

Clients were grouped into different age groups and risk categories for further analysis.

After preprocessing and feature engineering, the dataset contained 5,000 records and 38 variables.

### Exploratory Data Analysis

The project includes:

* Univariate analysis
* Bivariate analysis
* Multivariate analysis
* Distribution analysis
* Group comparisons
* Correlation analysis
* Interactive visualizations

Different charts such as bar charts, histograms, box plots, violin plots, scatter plots, and interactive Plotly visualizations were used to understand the data.

### Key Findings

Some of the major findings from the analysis are:

* The dataset contains clients from different age groups, with Older clients forming the largest group.
* Salaried clients represent the largest employment group.
* Income, expenses, debt, and investment values show significant variation and right-skewed distributions.
* Higher-income clients generally have higher expenses and debt.
* Age has a moderate positive relationship with investment portfolio value.
* Most clients belong to the Moderate Risk category.
* Younger clients generally show higher risk tolerance.
* High Risk clients have comparatively lower emergency-fund coverage.
* Retirement is the most common financial goal.
* Email and app are among the most preferred communication channels.
* Average client satisfaction is moderate.
* Regular client check-ins appear to be associated with better satisfaction in some client groups.
* Annual income has a strong positive relationship with monthly expenses.
* Income also shows positive relationships with credit score and total debt.

Important Correlations

Some important relationships identified in the analysis include:

Relationship	Correlation

* Annual Income & Monthly Expenses	0.89
* Annual Income & Credit Score	0.69
* Annual Income & Total Debt	0.66
* Age & Investment Portfolio	0.51
* Session Duration & Satisfaction	0.48

These correlations show associations between financial and client-service variables but do not necessarily imply causation.

### Business Recommendations

Based on the analysis, the project recommends:
* Providing personalized financial advice based on client risk profiles
* Strengthening emergency-fund planning
* Increasing regular client follow-ups
* Providing goal-based financial planning
* Giving additional support to younger clients with high debt
* Using client segmentation based on financial and demographic characteristics
* Providing flexible communication channels
* Considering age and financial life stage when providing investment advice
* Giving customized advice to clients with very high debt, income, or investment portfolios

This project demonstrates an end-to-end Data Analytics workflow, from data cleaning and preprocessing to exploratory analysis, visualization, insight generation, and business recommendations.
