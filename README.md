# loan-default-prediction-eda
**Project Overview:**
This project focuses on applying Exploratory Data Analysis (EDA) to loan application data, aiming to reduce the risk associated with lending. The goal is to identify patterns that predict potential loan defaults by analyzing client attributes and loan characteristics. Using EDA, the project explores how these variables influence the likelihood of a client defaulting on their loan repayments.

**Problem Statement:**
The loan industry faces challenges in approving loans for individuals with insufficient or non-existent credit history. This lack of data often results in higher default risks. The project aims to help a consumer finance company minimize financial losses by understanding patterns in data that indicate whether a loan applicant is likely to default.

**Business Objectives:**
Ensure that consumers capable of repaying their loans are not rejected.
Use EDA to identify key indicators of loan default, aiding in loan approval decisions.
Insights from the analysis can help the company adjust loan terms (e.g., higher interest rates for riskier clients).

**Data Understanding:**
The dataset used consists of three files:

application_data.csv – Client data at the time of loan application.
previous_application.csv – Client’s previous loan data, detailing loan status (Approved, Cancelled, Refused, etc.).
columns_description.csv – A data dictionary explaining each variable in the datasets.

**Analysis Approach:**

**1. Data Cleaning:**
Missing values were handled by either removing columns or imputing appropriate values.
Outliers were identified but not necessarily removed, as the focus was on understanding their impact.

**2. Data Imbalance:**
Checked for data imbalance, especially in the target variable (clients with payment difficulties).
Plotted graphs (e.g., bar charts, pie charts) to visualize the imbalance.

**3. Univariate and Bivariate Analysis:**
Explored individual variables to understand their distributions.
Segmented analysis on default vs. non-default cases.
Used correlation to identify relationships between variables that may predict loan defaults.

**4. Correlation Analysis:**
Conducted correlation analysis to find the top variables that influence loan repayment difficulties.
Focused on relationships between different variables, excluding the target variable.

**Key Findings**

  **1. Top Correlating Variables:** Identified the top 10 correlating variables for clients likely to default.
  
  **2. Default Indicators:** Found that certain client attributes, such as income level, loan amount, and previous loan status, are strong predictors of loan defaults.
  
  **3. Data Imbalance:** Noted a significant imbalance in the dataset, with fewer default cases compared to non-default ones. This required careful analysis to avoid bias in the results.

**Techniques and Tools Used**
  1. Python Libraries: pandas, matplotlib, seaborn
  2. Exploratory Data Analysis (EDA): Data cleaning, handling missing values, identifying outliers, performing correlation analysis.
  3. Visualization: Used various types of graphs (e.g., histograms, bar charts, scatter plots) to visualize data trends and patterns.

**Visualizations**
  1. Distribution of Loan Status: A count plot showing the frequency of each loan status (approved, cancelled, refused, unused offer).
  2. Income vs. Loan Default: A scatter plot showing how income correlates with loan default likelihood.
  3. Top 10 Correlating Variables: A heatmap illustrating the strongest correlations among key variables.


