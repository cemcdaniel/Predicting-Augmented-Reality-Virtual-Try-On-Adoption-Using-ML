Beyond the TAM: Using Machine Learning to Predict Consumer Adoption of Augmented Reality Virtual Try-ons
Overview
This quantitative comparative research study aims to assess the performance of the Technology Acceptance Model (TAM) in predicting Augmented Reality Virtual Try-on (AR VTO) adoption compared to various machine learning algorithms. The study also seeks to identify and compare key predictors of behavioral intention towards adopting AR VTO technology.
Objectives
Compare TAM's predictive performance against machine learning algorithms:
Multiple Linear Regression (MLR)
K-Nearest Neighbors (KNN)
Support Vector Regression (SVR)
Random Forest (RF)
Multilayer Perceptron (MLP)
Identify and compare key predictors of behavioral intention for AR VTO adoption across different algorithms
Uncover previously unrecognized factors influencing AR VTO adoption
Provide a nuanced understanding of technology acceptance across diverse consumer segments
Develop insights to enhance user experience and drive widespread adoption of AR VTO in online retail
Methodology
The study employs a quantitative comparative approach, utilizing both traditional theoretical frameworks (TAM) and data-driven machine learning techniques.
Data Collection
This study uses an archived dataset available at: https://data.mendeley.com/datasets/hwj7dj3xbb/3
Analysis
Implement TAM to predict AR VTO adoption
Train and evaluate machine learning models (MLR, KNN, SVR, RF, MLP) on the collected data
Compare predictive performance of TAM and machine learning models using appropriate metrics
Analyze feature importance and coefficients from each model to identify key predictors
Conduct comparative analysis of predictors across different models
Expected Outcomes
Comparative performance analysis of TAM vs. machine learning models in predicting AR VTO adoption
Identification of key predictors for AR VTO adoption intention
Insights into previously unrecognized factors influencing technology acceptance

Running the Notebooks
The notebooks should be run in numerical order. Note that the file 000 is the dataset used as input into the first notebook.
Notebook Execution Order
Data Preparation and Cleaning
000_AR_fashion_Originaldata_23.11Vietnamese (Input dataset)
001_Create Cleaned Dataset
002_Data Exploration
003_PCA Create Feature List
Model Development
004_BuildTestHarnesses-with extra models
005_TAM
006_Gradient Boost
007_KNN
008_Lasso
009_MLP
010_MLR
011_RF
012_Ridge
013_SVR
014_StatsModel MLR
015_ElasticNet
016_XGBoost
Analysis and Comparison
900_Cross Model Comparison for Document
