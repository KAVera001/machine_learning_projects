This repository contains various projects that I worked on during either my free time or they were part of the course.
_______________________
Files with classification models: 
1. MultivariateDataAnalysis_diabetes_classification.ipynb - The final project for Multivariate data Analysis. The project was completed in collaboration with Ksenia Alexander.
   The project aims to predict the diabetes class based on different health factors. Several binary classification models were
   tested (Logistic regression and SVM).
   The dimention reduction methods such as PCA and SVD were implemented and compared as well.
   
2. engine_crash_recognition.ipynb - binary classification problem. The main goal of the project is to predict the engine crash based on the previous behavior. We start with data explanatory analysis and proceed with modeling. Three models were tested: Logictic Regression, Decidion Tree Classifier and ensamble model Random Forest. Evalution metrics were compared to find the best model fit for the given data.
   
3. nba_players_classification.ipynb - binary classification problem. The project aims to predict 5YRS outcome for the nba players (will the career last 5 years or more) based on the statistics of the games in the beginning of the a player career. After Data preprocessing we use Decidion Tree Classifier for modelling.
   
4. notebook_classification_v1.ipynb - binary classification problem. The project aims to predict the infected device based on the various characteristic factors. LGBM Classifier was used for modeling.

_______________________
Files with regression models:
1. wine_score_regression.ipynb - the project aims to predict the wine quality score based on the factors such 'fixed_acidity',
 'volatile_acidity', 'citric_acid', 'residual_sugar' and etc. For modelling Linear Regression model was used.

2. diamond-price-prediction.ipynb - the goal of the project is to determine the diamond qualities that influence the diamond price the most and learn to predixt the price of the diamond based on the factors that characterize the diamond. We start with explanotory analysis and continue with modeling using 3 models: Linear Regression, Decision Tree Regressor and random Forest Regressor. After comparing the evaluation metrics we find the best model fit.
   
3. retail_sales_regression_notebook.ipynb - this project aims to predict the daily sales of the item for each store. We start with data analysis and feature engineering. We use LGBM Regressor to predict the daily sales.

_______________________
Time Series Modelling:
1. last-weather-prediction-timeseriesfinalproject.ipynb - the goal is to predict the weather 2 weeks ahead (14 days ahead). LSTM architecture was used.
   
2. Seasonal_Analysis_Fourier.ipynb

_______________________
Deep learning projects:
1. steel_defects_notebook.ipynb, resnet-augmentation.ipynb - deep learning project was completed in collaboration with Ksenia Alexander. Predicting the location and type of defects in steel manufacturing
The goal of the study was to predict the location and type of defects found in steel manufacturing. The study aimed to segment defects of each class (the classes were predefined by Severstal company) for each image, where each image may have no defects, a defect of a single class, or defects of multiple classes. To increase the size of training data, the study implemented image augmentation with the Albu- minations library and compared the results with and with- out augmentation. The study tested U-Net models with dif- ferent backbones to determine the most effective model for this task. The study used mean Dice coefficient and other possible metrics to evaluate the performance of the models. Overall, the study aimed to improve the accuracy of detect- ing and classifying defects in steel manufacturing, which is an important problem in the manufacturing industry.

2. deep_learning_two_layer.ipynb


