## Random Forest Classification Model for Determining Poisonous Mushrooms
Pramila Chaudhary

# Abstract:
The goal of this project is to build a classification model which determines whether a mushroom is poisonous or not 
for a pharmaceutical company who are interested in studying poisonous mushrooms for medicinal properties. I have used 
the dataset which has the mushroom's physical characteristics such as color, texture, height, cap-diameter etc. which identifies the poisonous mushrooms.

# Design:

  **Business Problem**

  Determining Poisonous Mushrooms for a pharmaceutical company who are trying to make drugs out of mushroom's medicinal properties
  which are used to prevent a wide range of illnesses including cancer, tumor, diabetes etc.

  **Solution paths:**
  
  Build a classification model to make predictions about poisonous mushrooms.

  **Impact hypothesis**

  We hypothesize that creating a classification model for pharmaceutical companies will help them 
  identify the poisonous mushrooms faster and accurately and save money for their further study.

  Primary Impacts: Over the past few years, many pharmaceutical companies are taking advantage of 
  this magic mushroom whose medicinal compounds have raised hundreds of million of dollars from private investors.

  Secondary Impacts: Successfully identifying and study will not only help the pharmaceutical companies but 
  also would help the human life by prevent wide range of illnesses including cancer, tumor, diabetes etc


  **Measures of success:**
   
   Accurately predicting poisonous mushrooms for medicinal compound studies and decreasing the false positive predictions.

# Data Set
  
  https://archive.ics.uci.edu/ml/datasets/Secondary+Mushroom+Dataset

  **Data Description:
    
  This dataset consists of 61069 number of instances  and 21 number of attributes
  
  Target and Features used for building models :

  Target: Class: edible=e(1) and poisonous=p(0)
  Features : cap-diameter, cap-shape, cap-color, does-bruise-or-bleed, gill-color, stem-height, stem-width, stem-color, has-ring, habitat, season. 
 
## Algorithms

  **Data Cleaning and Feature Engineering**

  -- Handling Missing Data:
  
  Removed all the columns with more than 70% missing data points.
  Converted null values to 0.
  
  -- Converting Categorical Features:

  label encoded all the categorical data into numerical values.
  Changed class categorical data to 1 and 0.
  
  **Classification Modeling**
  
  Each of the 5 models shown below are being fitted to 3 numerical features (before feature engineering) and for Accuracy and recall evaluation metric are calculated for each model.
  
  -- Random Forest Classifier Model before (feature engineering and hyperparameter tuning):
  Random Forest Classifier train score: 0.9999181245053356
  Random Forest Classifier  validation metrics: 
  Accuracy: 0.7956 
  Recall: 0.8117
  
  <img width="974" alt="Screenshot 2022-02-24 at 7 10 54 PM" src="https://user-images.githubusercontent.com/89863226/155646766-8821fc29-4364-4134-9a7a-028153d42cac.png">

  
  Random forest model showing the best results in the above graph. 
  
  Further adding more engineered features and tuning the hyperparameter to overcome the overfitting of the model
  
  The  following evaluation metrics are achieved by training, validating and testing the dataset using RF classifier.
  
  Random Forest Classifier validation metrics for test data set: 
  Accuracy: 0.9885 
  Recall: 0.9865

# Tools
  
  1. Pandas and Numpy for data acquisition, cleaning, and feature engineering
  2. Sklearn for modeling and parameter tuning
  3. Matplotlib and Seaborn for data and model visualization

# Communication:
  Uploaded the Presentation PDF on my repo.
