# CORONAVIRUS TWEET SENTIMENT ANALYSIS

![tweet header](https://user-images.githubusercontent.com/107639055/188276827-a3b1e9d2-88f2-4b07-80b0-e66da7915abd.png)

### 📋 PROBLEM STATEMENT:

This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then.

###  🎯 OBJECTIVE: 

The CoVid-19 pandemic has shaken the very foundation of society wherein people were forced to live inside their houses because of the lockdown being imposed and also the livelihood of almost every section of the society was impacted. 

The objective of our analysis revolved around knowing the sentiments of people from their tweets on Twitter as Twitter is one of the prime means of expression over social media.

###  APPROACH:
-	Text Preprocessing
-	Exploratory Data Analysis 
-	Model Preprocessing
-	Model Training

### 📘 ALGORITHMS USED:
- Logistic Regression with Grid Search CV
- Decision Tree Classifier
- XG Boost 
- KNN
- SVM Classifier for both Count Vector and TF ID Vectorization techniques.

### PROBLEM FACED:

-	Text preprocessing.
-	Vectorization.
-	Model Training and performance improvement

### CONCLUSION:
-	 We conclude that the machine is generating the best results for the Logistic Regression with Grid Search CV (count vectorizer) model with an Accuracy of 78.28% followed by the Logistic Regression with Grid Search CV (TF/ID vectorizer) model with an Accuracy of 77.43%.
-	 Also, we observed that no overfitting is seen for the data, and we can deploy this model.
-	Even being in the unprecedented situation of CoVid-19, people's positive sentiments outnumbered negative sentiments. 
-	However, negative sentiments also has a significant chunk which various Government agencies, NGOs, etc can use to help boost the morale of the people and then
-	In the future ,we can repeat the analysis and compare it with the present sentimental analysis to gauge the impact of the initiatives on the ground.

### 📜 CREDITS:

[Gaurav Malakar](https://github.com/gauravmalakar08) | [Anup A. Jambulkar](https://github.com/anup-anny) | [Ankit Walde](https://github.com/AnkitWalde) | [Anil Bhatt](https://github.com/anilbhatt-DataAnalyst) | [Vibhu Sharma](https://github.com/vbhsharma7)

### 📚 References
Random Forest Regressor - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html 

Gradient Boosting Documentation - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
