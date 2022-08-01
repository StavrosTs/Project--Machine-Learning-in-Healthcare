# Project Machine Learning in Healthcare
Stroke Predictions
    
1. Authors
    - Stavros Tsiloglou
    - Nikos Kefalas 
    
2. Cleaning & Analysis
    - First, we read the dataset in order to find empty rows or unnecessary columns that we should drop.
    - Then we visualized our data, so we could:
        - Find highly correlated columns.
        - Find if our dataset is unbalanced.
        - See the distribution of our data.
        - Spot outliers.
    - The steps we took & the changes we made:
        - Replaced our classes with 0 & 1.
        - Excluded the outliers.
        - Transform categorical variables. (We tested one-hot encoding & feature hashing)
        - Filled empty rows with total average of respective column.
        - Scaled our dataset so we can normalize the data.
        - Balanced our dataset.
        - Run different classifiers (RandomForest,LightGBM & XGBoost) in order to find the best one.
        - Finally, we used GridSearchCV to find the best hyperparameters.

3. Presentation
    - Exported the necessary graphs & confusion matrix for our presentation.
    - Thank you for reading!
    




