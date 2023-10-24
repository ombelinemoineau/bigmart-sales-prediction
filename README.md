# bigmart-sales-prediction
The goal is to know the sales of products in the outlets


BigSmartSells is a dataset which contains different items/products with their information, and the outlet they came for (and their information)

Benefit : to manage the stocks

Difference with the credit card database:
- we have to add LabelEncoder because we have features that are not numerical
- import LinearRegression because we are not going to do classification but regression
- we will not use the accuracy score but mean_squared_error because we have not only 2 values but many
