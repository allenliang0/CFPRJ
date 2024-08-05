This is a readme file. The code in the project are stored in this zip, with the name CFPRJJY.ipynb This is a Jupyter Notebook file. 

Tweet.csv, Company.csv and Company_Tweet.csv are downloaded from Kaggle where they contain financial tweets about the top companies from 2015 to 2020. Link can be found here https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020

test_accuracy.csv and train_accuracy.csv are used to test the performance and accuracy between the sentiment analysis models. Link can be found here https://www.kaggle.com/datasets/yacharki/amazon-reviews-for-sa-binary-negative-positive-csv

By data cleaning and preprocessing, data_aapl_top.csv, data_goog_top.csv and data_amzn_top.csv contains the financial data and top 10 tweets of each day of the company all the way from 2015 to 2020. 

aapl_gpt.csv, goog_gpt.csv and amzn_gpt.csv contains an extra column where the sentiment of the top 10 tweets of the day are analysed. Therefore, these 3 datasets can be used in the code straight away by LSTM prediction. 

Note that sentiment analysis took the author many hours to do, therefore, using the csv files already store in this zip is recommended. 

Simply download these csv, use panda csv read function (remember to change to the correct path) and the code in the CFPRJJY.ipynb can manage a quick LSTM stock prices prediction. 