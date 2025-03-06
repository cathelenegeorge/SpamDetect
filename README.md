# SpamDetect
This project aims to detect whether it is spam or not with the help of Logistic Regression.
## Steps involved:
### 1.Import Required Libraries: 
Import and install dependencies ,here I have mentioned all the dependencies in a req.txt file ,this can be installed using the command "pip install -r req.txt"
Using a virtual environment is suggestible
### 2.Load the dataset:
load the dataset "spambase.csv" with the help of pandas library, followed by dividing the dataset into target(y) and predictor variables(x) , then divide the dataset 
into training and test split set 
### 3.Model Building:
Build a Logistic Regression model and train the model and use the model to make predictions for X test
### 4.Evaluate the model:
Evaluation of the model is done with the help of evaluation metrics such as accuracy score, precision score, F1 score and confusion matrix
### 5.Visualise the Confusion Matrix :
This is done with the help of heat map feature in Seaborn Library
