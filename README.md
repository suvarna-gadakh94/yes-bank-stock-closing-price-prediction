# yes-bank-stock-closing-price-prediction

In this project, we got single CSV files as input. The CSV files are data_YesBank_StockPrices.csv, this file consists of around 186 rows and 5 columns. As we have a single data set so we decide to work in collaboration with teammates. First, we imported all required libraries for further evaluation Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock's closing price for the month.

secondly, we have done data understanding and overview of provided data. we found that most of the data are in int data type and only one column is in string ( object ) type data. after we loaded provided data set into the colab environment using pandas then we did some data cleaning by adding extra required columns, removing an unwanted column, column rename, and so on. after cleaning the data we did data wrangling where we execute a program to get specific outcomes from the given data set , then we visualize the process data for graphical representation. The next task is feature engineering in this step we did Feature engineering is the pre-processing step of machine learning, which is used to transform raw data into features that can be used for creating a predictive model using Machine learning or statistical Modelling. Feature engineering in machine learning aims to improve the performance of models. Feature engineering in ML contains mainly four processes: Feature Creation, Transformations, Feature Extraction, and Feature Selection. the most important and tough part is the machine learning part in this part we have to select two variables 1) the dependent variable and 2) the independent variable. by using a different type of regression like

Linear Regression Linear regression is one of the most basic types of regression in machine learning. The linear regression model consists of a predictor variable and a dependent variable related linearly to each other. In case the data involves more than one independent variable, then linear regression is called a multiple linear regression model. Ridge Regression This is another one of the types of regression in machine learning which is usually used when there is a high correlation between the independent variables. This is because, in the case of multi-collinear data, the least square estimates give unbiased values. But, in case the collinearity is very high, there can be some bias value. Therefore, a bias matrix is introduced in the equation of Ridge Regression. This is a powerful regression method where the model is less susceptible to overfitting. Lasso Regression Lasso Regression is one of the types of regression in machine learning that performs regularization along with feature selection. It prohibits the absolute size of the regression coefficient. As a result, the coefficient value gets nearer to zero, which does not happen in the case of Ridge Regression. after we trained the model for future prediction, in the end, we extracted the conclusion
