# Big-Mart-Sales-Prediction-Analysis
An analysis of the Big Mart retail dataset to predict sales and provide insights for improving profitability. This project is part of the MattYoungMedia data analyst assessment.

### Introduction
The objective of this analysis is to explore and analyze a retail dataset to gain insights into customer behavior and make recommendations for improving sales and profitability.

### Data Cleaning and Transformation
- The dataset was initially cleaned by removing duplicate entries and handling missing values using imputation techniques.
- Categorical variables were encoded using one-hot encoding for further analysis.
- Feature scaling was applied to normalize the numerical variables.

### Exploratory Data Analysis
- The dataset contains information on item attributes, sales, and outlet details.
- The average sales were highest for items with higher maximum retail prices (MRP).
- There was a negative correlation between item visibility and sales.
- Outlet establishment year had a weak positive correlation with sales.
- Several significant relationships were identified through visualizations and statistical analysis.

### Feature Engineering
- New features were created, such as "Total_Item_Sales" by combining item weight and quantity sold.
- Price per unit weight was calculated to understand price variations based on weight.
- Outlet age in years was calculated by subtracting the establishment year from the current year.

### Model Building
- Multiple regression models, including linear regression and random forest, were built to predict sales based on various features.
- Model performance was evaluated using metrics such as mean squared error (MSE) and R-squared.
- The random forest model outperformed other models, with lower MSE and higher R-squared.

### Results and Recommendations
- The analysis revealed that item MRP, visibility, and outlet age are important factors affecting sales.
- Recommendations include optimizing pricing strategies based on item MRP, improving visibility of high-sales items, and exploring opportunities to rejuvenate older outlets.

### Conclusion
In conclusion, this analysis provided valuable insights into customer behavior and sales patterns. By leveraging the recommended strategies, retailers can improve their sales and profitability. Further research and analysis can be done to explore additional factors and enhance the predictive models.

