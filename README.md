# ipl2020_player_score_prediction
fliprhackathon 


Firstly, We spilt (80-20) the provided train data Excel File into training (80%) and testing (20%) data for the model. Then we tested with various models such as Linear Regression, Ridge Algorithms, Random Forest, etc from SK Learn and XGBoost Libraries. (Root of Mean Square Error) RMSE from SK Learn were used to judge if the model is accurately predicting the test values and the resulting     RMSE = 15.9. Then utilizing the RandomCV library from SK Learn we identified the best parameters for the model.

Finally, we imported the XGBoost Library and fitted the necessary features and trained the model to predict next years total runs of a batsman. In this case the data used to train is the train data of the provided Excel File (of the problem statement). i.e. total runs (2018), HS, MAT, etc. of train data. 
Then the model predicted the total runs (2020) of the batsman using the data based on the test data sheet of the provided Excel File, i.e. total runs (2019), HS, MAT, etc. of test data.
The solution file is attached along with this file.
