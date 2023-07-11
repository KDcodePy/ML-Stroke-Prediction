# ML-Stroke-Prediction
## Analysis and Model Prediction on [Healthcare Dataset with Stroke](https://github.com/KDcodePy/ML-Stroke-Prediction/blob/main/healthcare-dataset-stroke-data.csv)
### Author: Kim Hazed Delfino

### Business Problem: 
Determine whether a Health Insurance client should pay a Premium for being high-rish of stroke and Increase Company's profit margin by reducing unexpected insurance claims and improving risk-analysis per client. 

## Methods
 - remove all duplicates to avoid repeating data
 - correct all data inconsistencies (mislabled, unnecessary extra character)
 - Impute missing values to keep data integrity and avoid model prediction errors
 
## Exploratory Data Analysis
 - Quick glance of Age and Gender Distribution:
 ![Age range and Gender in this dataset](https://github.com/KDcodePy/ML-Stroke-Prediction/blob/main/images/output_age_gender.png)
 
 Here we can see that the majority in this dataset are Female and we have broad range of age but most common are ages early-mid 40s and 80s
 
 
 ---
 
 
 ![stroke barplot](https://github.com/KDcodePy/ML-Stroke-Prediction/blob/main/images/output%20-%20stroke_bar.png)
 
 This Graph represents the occurrences of stroke and their current health conditions, Location, and if they have bad smoking habbits 
 
 
 ---
 
 
 ![displot](https://github.com/KDcodePy/ML-Stroke-Prediction/blob/main/images/stroke_displot.png)
 
 In this graph we can see the frequency of stroke occurrence relative to Age and if they have known Heath Disease 
 
 
 ## Models
 - KNearest_Neighbors -  also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.
 
 - RandomForest - is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time
 
 - XGBoost -  is also a boosting algorithm in machine learning which is an extreme version of gradient boosting. In gradient boosting, there is no implementation of regularization, whereas XGBoost is a regularized form of gradient boosting algorithm
 
 
Recommendations: 
 - more data means more opportunity to find commonality for analysis and paterns for model predictions, we can't go wrong with adding more data in our dataset
 - gather more relavant data with higher concentration of clients with history of stroke so that our model can generalize and better learn the patterns from clients with actual stroke history
 
 Limitations & Next Steps:
 - the use of imblance dataset in machine learning model limits our capability to fine-tune our models to better understand patterns in our dataset
 - next Step - Explore better techniques or models that will perform better on handling imblance dataset.
  
 ### For further information
for any additional question, please contact me at my [email](delfino.kim@yahoo.com)
