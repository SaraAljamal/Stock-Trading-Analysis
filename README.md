# Stock-Trading-Analysis
An analytical project focused on stock trading data, performing descriptive, predictive, and prescriptive analysis to uncover insights and guide decision-making in the financial market. The project includes feature selection, regression models, and optimization algorithms to predict stock prices and trading behavior.

_**Problem Statement**_
The goal is to analyze stock trading patterns and predict future stock prices (high and low) using machine learning models. The project also aims to apply optimization techniques to help traders minimize their spending on stocks.
Dataset
The Project involves 2 identical datasets with different target column in each which are high” and ‘low”, each dataset contains 28012 records and 13 features.
 
_**Project Workflow**_
1. Descriptive Analysis: Conducted on one dataset to understand trading behavior and key trends. Visualization and analysis were performed on features such as trade volume, market activity, and price variations.
   
2. Predictive Analysis:
  - Feature Selection: Applied techniques like SelectKBest to select the most relevant features for predicting stock prices. 
  - Regression Models: Linear Regression, Decision Tree, and K-Nearest Neighbors (KNN) were used to predict both the "high" and "low" stock prices. 
  - Evaluation: The models were evaluated using RMSE, MAE, and R2 metrics. Comparisons between models were made to identify the best-performing technique.

3. Prescriptive Analysis: Grey Wolf Optimization (GWO), Multi-Verse Optimization (MVO), and Sin Cosine Algorithm (SCA) optimization algorithms were applied to find the optimal stock quantities to minimize costs.

_**Tech Stack**_
- Python: The main programming language used
- Pandas: For data manipulation
- Numpy: For numerical operations
- Scikit-learn: For model building and evaluation, and data preprocessing
- Matplotlib & Seaborn: For data visualization
- Google Colab: The main tool used for coding and experimentation

_**How to Use**_
1.	Stock_Trading_Analysis.ipynb Notebooks:
o	The First part contains the descriptive and predictive analysis parts, while the second contains the perspective analysis 
o	To run each notebook, open the it in Google Colab:
- Click on the notebook file (Stock_Trading_Analysis.ipynb).
- Choose "Open in Colab" from the GitHub file preview.
- You can run the cells sequentially to see the steps and results.

2.	Stock_Trading_Analysis Report:
- The report (Stock_Trading_Analysis Report.docx) includes: 
1- A comprehensive review of the tools, techniques, and activities of data analytics
2- Reviewing and evaluating the work done on descriptive, predictive, and prescriptive analytics.
- You can view or download the report directly from the repository to understand the project background and conclusions.

