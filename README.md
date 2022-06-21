# Wine-Quality-Project
Machine Learning Course Project

Milestone 2:
        The data was produced by testing a variety of different variables that contribute
to the wine quality taste. In this scenario, I am only testing the first three variables to
see how well alone do they contribute to the taste of wine. The first variable is fixed
acidity, which is acids that are involved with wine that do not evaporate readily. The
second variable is volatile acidity, which is the amount of acetic acid in wine. In high
levels, this can lead to a vinegar taste. The third variable is citric acid, which is the
‘freshness’ and particular flavor to wines. Lastly, the last variable is the quality of the
wine between 0-10(0 the worst, 10 the best).
    

Milestone 4:
        According to the linear regression model, It is not the best model. With a score of
0.153, it is a terrible model. With a 80/20 split test/train, it guessed correctly 162 out of
320 testing data and guessed incorrectly 158 out of 320 leaving it at 50% accurate in
predicting the correct results. However, with the Decision Tree Regressor Algorithm
with a max depth of value 7, gave the decision tree algorithm a score of 0.3320 which is
better because the correct predictions were valued at 52.5% compared to the linear
regression algorithm at 50%. I chose max depth of 7 because it didn’t overfit the data
and the predictions were pretty wide spread compared to lowering the max depth which
led to predictions of 5 or 6. However, overall, both algorithms were still not the best and
maybe without the other predictor variables that I had not chosen, it would’ve been
better to include more predictor variables within my data. Also, by the Decision Tree
Classifier, it hit a score of 0.79, which overall isn’t as good. With only 136 being the
matching results, only 184 were not the same. With the Random Forest Classifier with
n_estimators of 50, it is scored around approximately 0.65+. Random Forest Classifier
works a little bit better and also considering that I included all the predictor variables
instead of the first three
