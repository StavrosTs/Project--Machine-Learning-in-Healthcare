# Project Machine Learning in Healthcare
Stroke Predictions
    
1. Authors
    - Stavros Tsiloglou
    - Nikos Kefalas 
    
2. Cleaning & Analysis
    - First, we read the dataset in order to find empty rows or unnecessary columns that we should drop.
    - Then we visualized our data, so we could:
         i. Find highly correlated columns.
        ii. Find if our dataset is unbalanced.
       iii. See the distribution of our data.
      iiii. Spot outliers.
    - The steps we took & the changes we made:
         i. Replaced our classes with 0 & 1.
        ii. Excluded the outliers.
       iii. Transform categorical variables. (We tested one-hot encoding & feature hashing)
      iiii. Filled empty rows with total average of respective column.
        iv. Scaled our dataset so we can normalize the data.
         v. Balanced our dataset.
        vi. Run different classifiers (RandomForest,LightGBM & XGBoost) in order to find the best one.
       vii. Finally, we used GridSearchCV to find the best hyperparameters.

3. Presentation
    - Exported the necessary graphs & confusion matrix for our presentation.
    - Thank you for reading!
    




