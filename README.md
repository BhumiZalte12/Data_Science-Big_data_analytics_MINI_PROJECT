DSBDA MINI PROJECT

created by : - Bhumi Zalte

TOPIC  :-  MOVIE RECCOMADATION and popolar movie prediction system

Main Objective:

The main agenda of this project is:

Perform extensive Exploratory Data Analysis(EDA) on the movie rating Dataset.

Build an appropriate Machine Learning Model that will help various users to predict their respective Ratings based on certain features.

ABSTRACT :- In this project we have performed exploratory data analysis on given dataset. And created a model that can predict the rating of the movie.
This project presents a Movie Rating and Prediction System developed using data analytics techniques. The system involves several stages including data collection through Google Form surveys, data cleaning, and the development of predictive models. The collected data is divided into two parts: one for training model development and the other for testing, optimizing, and evaluating the model.

In the training phase, various machine learning algorithms are applied to the cleaned dataset to develop predictive models. These models are trained to predict movie popularity based on various features such as genre, cast, director, and user ratings. The performance of each model is evaluated using appropriate metrics to ensure accuracy and reliability.

In the testing, optimizing, and evaluating phase, the trained models are tested on a separate dataset to assess their predictive performance. Optimization techniques are applied to fine-tune the models for better accuracy and generalization. Finally, the optimized models are evaluated based on their ability to predict popular movies among all the movies in the dataset.

The Movie Rating and Prediction System aims to provide valuable insights into the factors influencing movie popularity and to assist users in making informed decisions about movie selection. By leveraging data analytics techniques, this system offers a data-driven approach to understanding and predicting movie preferences.

Feature description :
(columns)
index
budget	
genres
homepage	
id	
keywords
original_language
original_title
overview
popularity	
runtime	
spoken_languages
status	
tagline	title	
vote_average	
vote_count	
cast	
crew	
director

For the modeling part, i used LinearRegression, DecisionTree Regressor, RandomForest Regressor , Supprotvector Regressor & ExtraTree Regressor. From all these models ExtraTree Regressor perform well compared to the other models.So i selected ExtraTree Regressor for model creation.
