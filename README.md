## This InsurancePrediction ML model is trained as per the following steps:

The Data was imported as a csv file from [Kaggle](https://www.kaggle.com/datasets/awaiskaggler/insurance-csv) <br><br>
Categorical columns and features in the dataset were encoded through OneHotEncoder. <br><br>
Scaling of all columns was standardised using MinMaxScaler before splitting into training and testing sets. <br><br>
A ratio of 8:2 was followed for training and testing with a random state of 42 to ensure same data for every iteration. <br><br>
Linear Regression was the main algorithm used here to train the model. <br><br>
Cost functions like Mean Absolute Error, Mean Squared Error and Root Mean Squared Error were determined as a final step. <br><br>
