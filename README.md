# Heart_disease_prediction

# CONCLUSION


## in this project we have to predict which patient has heart disease or not on the basis of given attributes.

### During importing Dataset the data was seprated in independent and target variable so we concatenate the data and i stored them in one dataframe.

### During Basics check i found that data has unnecessary column patiend_id so i drop it then id did Domain analysis.

### in data preprocessing during Data conversion i checked that is there need to convert of data categirical to numerical form , then i fing a column that was thal was showing object .. so i encoded manually using map function.

### before check outliers i seprate categorical and numerical data in diffrent variable Then i checked outliers on numerical variable and i found that some column has outliers, so we removed outliers by using IQR method.

### Then i create model

### The Output feature colum heve binary class feature so for this reason we have chosen this problem statement as binary class classification and then we use diffrent Algorithm to check the performance of the diffrent Algorithm this can be checked using f1_score and compare it down by with diffrent model accracy , so whichever model showing highest accuracy score w have chosen that model predction.


## I used diffrent ML algorithm
- 1. Logistic Regression
- 2. RandomForest Classifier
- 3. SVM Classifier
- 4. Decision Tree Classifier
- 5. AdaBoostClassifier
- 6. Gradient Boosting Classifier
- 7. XGB Classifier
- 8. Naive Bayes Classifier
- 9. KNeighbors Classifier
     
### Out of these Algorithm there is performed some algorithm better than other:
- 1. Logistic Regression
- 2. RandomForest classifier
- 3. ADABoost Classifier
- 4. GradientBoosting Classifier
- 5. XGB Classifier
  
### After Hyperparameter Tuning some model has performing same there is no variation before and after hyperparmeter tuning that model is Logistic Regression, Random forest classifier and XGBoost classifier but I selected RandomForest classifier

### RandomForest classifier

### After Hyperparameter tuning I found that some model has giving well accuracy on data as compare to all model so We have choose this model for future prediction of heart disease predction of patient that in feature if someone has heart disease problem we can predict quickly by using our model .
