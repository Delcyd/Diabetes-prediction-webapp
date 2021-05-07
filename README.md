# Diabetes-prediction-webapp
This is a simple Flask web app which predicts whether a patient is having diabetes or not.


The Code is written in Python 3.6.10. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository

pip install -r requirements.txt

Used two datasets, Train data and Test data from Kaggle

Language – Python, Anaconda

Other libraries for analyzing & visualization: Pandas, Numpy, Matplotlib, Seaborn

AI/ML : Scikit-Learn , ML models

Web Frameworks : Flask

Hosting: Heroku (side projects & demos)

Tracking & SC: GitHub





_________________________________________________________________________________________________________________________________________________________________________________




PROCESS

Since data is in form of excel file we have to use pandas read_excel to load the data

We will be using train and test data. We can do some data pre-processing and remove variables which are not needed

After loading it is important to check the complete information of data as it can indication many of the hidden infomation such as null values in a column or a row. Next step is Feature generation, here we mainly work on the data and do some transformations to extract unknown variables or create different bons of particular columns and clean the messy data.

Check whether any null values are there or not. if it is present then following can be done: Imputing data using Imputation method in sklearn Filling NaN values with mean, median and mode using fillna() method Describe data, which can give statistical analysis

Mainly work on the data set and do some transformation like creating different bins of particular columns ,clean the messy data so that it can be used in our ML model . This step is very important because for a high prediction score you need to continuously make changes in it

Do some EDA, analysis & data visualisation to understand the relationship between different independent variables and the relationship between the independent variables and the dependent variables

Prepare categorical variables for model using label encoder - convert categorical text data into model-understandable numerical data

Divide the data set into test and train - all our data is numerical after label encoding so we split the data into test and train & predict the price with our test data set

Building Model - measure the performance of a better and more tuned algorithm, & using different Classifier Technique and comparing them to see which algorithm is giving better performance. Evaluated various models for computing expected future prices and classifying whether this is the best time to buy the ticket. Finally after the above steps. Predict the air tickets prices, and the performance of the models is compared to each other. Later deployed the model and evaluate the efficiency of the predictions.

UNSUPERVISED TMODELS USED: Random Forest Classifier: 90.04% KNN : 75.7% Xgboost : 87.48% Gradientboost : 87.59% ACCURACY SCORE : 93:14%
