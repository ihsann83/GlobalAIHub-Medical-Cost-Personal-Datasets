# GlobalAISummerCamp_Medical-Cost-Personal-Datasets

Data Set: https://www.kaggle.com/datasets/mirichoi0218/insurance

In this project, an end-to-end data science application using the dataset given above will be tried to be improved. 
The aim of the project is to ensure that a person's health according to the given variables estimating approximately how much their insurance will cost. 
When creating the project, I followed the steps below 


# 2. Necessary Libraries

● I added the libraries to be used in the project

# 3. Exploratory Data Analysis

● I tried to get meaningfull conclusions from the data by examining and analyzing it. Hence, I examined;

○  the distribution of BMI (Body Mass Index)

○  the relationship between "smoker" and "charges"

○  the relationship between "smoker" and "region".

○ the relationship between "bmi" and "sex".

○ the "region" with the most "children".

○ the relationship between "age" and "bmi".

○ the relationship between "bmi" and "children".

○ Is there an outlier in the variable "bmi"? Check it out.

○ the relationship between "bmi" and "charges".

○ the relationship between "region", "smoker" and "bmi" using a bar plot.

● I tried to use data visualization techniques as much as possible, when examining the data, 

● I added the meanings I have extracted from the analysis as a comment line.

# 4. Data Pre-Processing

● In this section, I made the data ready to train the model.

● I used One-Hot Encoding technique to make the categorical variables usable

● I divided the data into X_train, X_test, y_train, y_test.

● I scaled the data set by MinMax Scaler.

# 5. Model Selection

● I used several regression models such as; Linear Regression, Ridge Regression, Lasso Regression, SVR, Decision Tree and Random Forests. I trained them with pre-processed data.

● I examined the performance of the selected models using cross-validation.

● I optimised them with Grid Search 

# 6. Evaluating the Model

● I evaluated the models with the metrics; R2, MAE, MSE and RMSE. Also I visualised the evaluation of the models.


# 7. Prediction

● I optimized the hyper-parameters of the selected model with Grid Search.

● I prepared the first line of the data set to be predicted with my model.

● I made the prediction with the first line of the data set.










