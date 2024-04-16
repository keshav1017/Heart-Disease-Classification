# Heart-Disease-Classification
This project looks into various Python based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

Detailed desscroption of this project is in the following order:

1. First I maually analysed the data using numpy, pandas, seaborn and matplotlib itself to get a brief view of data. Such as plotting heart rate frequency according to sex of the person and correlating every attrubute to every attribute using seaborn's heatmap.

2. After then getting a rough idea of the trend of the data, I started modelling of data by first spliting the data (X and y) into training and test data set.

3. Then I used several machine learning models such as KNeighborsClassifier, LogisticRegression and RandomForestClassifier to get the best possible score for our problem. This was done by comparing all the scores of the respective models.

4. Then I did hyparameter tuning to enhance the score of the models by changing certain hyperparameters of the LogistecRegression model.

5. Then I used several evaluation metrics usch as accuracy, precision, recall and f1_score to evaluate the model in a more detailed way.

6. Feature Importance is very crucial for any model and I too did the same for my model.

7. Then I used Gradiend Boosting such as XGBoost, LightGBMBoost and CatBoost to further enhance the results.
