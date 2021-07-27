# Titanic---Machine-Learning-from-Disaster
Config files for my GitHub profile.
Kaggle Titanic Modeling Competition (Python)
Project background: Participated in the Kaggle Titanic Data set modeling Competition to construct a classification model to predict passenger survival rate
Data processing: Extracting appellations from passenger names as new variables through feature engineering, and using them as groups to fill in missing age values; The median and mode are used to fill in other missing values. Ticket price and age are sorted
Data modeling: Logistic regression, support vector machine, decision tree, random forest, XGB and other models were tested. Parameters were adjusted through grid search, model selection was carried out according to confusion matrix and AUC value, and feature importance was obtained by using gini importance of random forest
Project Results: XGB was selected as the optimal model, and its AUC in the test set was 0.82. The model showed that social class, gender and class of cabin had significant influence on whether passengers survived or not
