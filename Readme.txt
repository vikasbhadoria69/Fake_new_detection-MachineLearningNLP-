I have tried to detect the fake news in this tutorial. The dataset is taken from
https://www.kaggle.com/c/fake-news/data#.
We here have already labelled data. 
Step 1 = to seperate dependent features and independent features.
Step 2 = to pre process our data. So it can be machine readable. We can use CountVectorizer, TfidfVectorizer or HashingVectorizer for this. All of these models are present in sklearn. I have used CountVectorizer here but you can tweet the my code and try using other possiblilties.
Step 3 = to split the data to train and test.
Step4 = Use machine learning models to predict the results. I have used 2 models here. 
MultinomialNB Algorithm
Passive Aggressive Classifier Algorithm

Results of both can be found in the Ipnb.