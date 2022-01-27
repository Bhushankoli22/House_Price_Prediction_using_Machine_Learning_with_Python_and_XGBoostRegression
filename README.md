# House_Price_Prediction_using_Machine_Learning_with_Python_and_XGBoostRegression
In this project I am trying to predict House Price using ML with the help of Python and XGBoost Regression method.
Goal of the project : 
To predict the cost of houses, based on Boston House Price Dataset.

Explaination : First select or load the Boston House Price Dataset, into the Colab research notebook. But , we cannot feed this dataset directly to the machine learning model.For that we need to do a lot of processing of the data. So we need to do the Data Preprocessing steps.
We will feed the data into dataframe and then in this dataframe we will do some processing. After that our data will be suitable and compatible to feed to the machine learning model.
Once we process the data we have to do the Analysis on the data, so we need to find the correlation between various features.
As we can see our dataset has 13 features and 1 price column, so we try to see which 13 of these features are interrelated. This process is done in the data analysis step.

So once we had done with data analysis, we can split the data set into training data and testing data which is called as train test split.
So we need to feed this training data to our XGBoost Regression algorithm.And we will evaluate our model with the help of testing data.Because the traing has to be done with the one type of data and the testing has to be done with new data. This is the reason we are splitting it.
XGBoost Regression is a decision tree, classification kind of algorithm.It is very much useful for regression cases. There is also XGBoost classifier and HC Boost Regression as our problem statement is a regression where we need to predict a continuous value or a numerical value which is the price we used a regressor model.
