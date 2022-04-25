# PASH Estates Inc.
Link to the [House Prices Kaggle Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

1) What is the problem that you will be investigating? Why is it interesting?

Buying a house remains one of the biggest buying decision that people make in their lifetime. It is difficult to predict the final sale price. There are people who struggle after knowing the expenses they will face in the future. This project will help with the decisions people will come up with. It will help in buying a perfect house which will satisfy their financial needs as well.

2) What reading will you examine to provide context and background?

Reading the graphs related to sale prices will provide more context and background. There are a few variables that we will examine such as:
total number of bathrooms, 
whether remodelling took place, 
age of house after remodelling, 
landscape of the house, 
new garage quality obtained by multiplying garage quality with number of cars the garage could fit, 
total square feet of the house, and  
consolidated porch area.

3) What data will you use? If you are collecting new data, how will you do it?

The dataset from Kaggle will be used. The training dataset has a total of 1460 observations with 81 variables while the test dataset has one less variable since we have excluded the predicted variable, SalePrice. These are the data that we will be using in order to examine house prices in Iowa.

4) What method or algorithm are you proposing?

We can use Multiple Linear Regression. It is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. Multiple linear regression is used to model the relationship between a continuous response variable and continuous or categorical explanatory variables.
XGBoost algorithm can be used. XGBoost is a popular and efficient open-source implementation of the gradient boosted trees algorithm. 

5) How will you evaluate your results?

Qualitatively we can expect to see higher sale prices when there are much more variable which will affect the prices in the future.
Quantitatively we can use scatterplots and boxplots to evaluate our results between the observations and sale prices. It will give a visual representation of the dataset we have gathered.

The files final report and supplementary material are posted both in the docs folder as well as outside in the Data science project branch. Also, the train.csv dataset file is uploaded. And the PASH Estates Inc pyhton notebook is also uploaded.
