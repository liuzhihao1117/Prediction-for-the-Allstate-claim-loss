# Prediction-for-the-Allstate-claim-loss
in this project the goal is to predict single claim loss based on dataset provided by Allstate insurance company. The dataset contains over 180000 observations with 131 variables including 116 categorical variables,14 numerical variables and one target variable named Loss, and Kaggle has already split data into training and testing set. Model performance is being evaluated by the error between prediction and actual data. 
# Algorithms and Techniques
Firstly, we choose linear regression to deal with this kind of problem. Because the dataset has 130 predicting variables, we might need to try penalized method like Ridge and LASSO regression, they can shrink coefficient in magnitude to select significant variables and they can be trained extremely fast.

Secondly, because of this large dataset with 132 variables, we choose Random Forest and XGBoost to do analyze. Random Forest ensemble prediction power of many weak learners to form a strong learner, which provides strong performance. XGBoost is derived from Gradient Boosting Machine, which is a boosting tree based method similar to Random Forest, XGBoost improves the algorithm by adding well-defined regularization term to prevent overfitting.

Finally, we try to ensemble these methods together to get a new model, aiming to construct a strong learner from several weaker learners. The idea behind this is that different models tend to capture features of data from different aspects, ensemble them together ideally will form a model that has the ability to capture data variation from every side, which potentially would deliver better results.
# Software
Rstudio Python
