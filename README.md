### Sentiment_Analysis

- A definitive guide: https://monkeylearn.com/sentiment-analysis/

- A blog explaining ML algorithms: https://monkeylearn.com/blog/machine-learning-algorithms/

- Ebook: http://www.cs.unibo.it/~montesi/CBD/Articoli/SurveyOpinionMining.pdf


We perfomed Text Classification on the Covid_19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then.
The names and usernames have been given codes to avoid any privacy concerns.
Data size = (3798 x 4).

Columns:
1) Location
2) Tweet At
3) Original Tweet
4) Label

The first notebook primarily breaks down the data with explanatory analysis with data visuals. The later notebook primarily focuses on using Machine Learning algorithms such as Support Vector Machine to classify the textual data into 3 classes (Positive, Neutral and Negative). The choice for SVM was quite understandable, given other algorithms such as Random Forest Classifier and Multinomial Naive Bayes had worse accuracy to predict whether a tweet relating to Covid-19 was either Positive, Neutral or Negative. The final model had an overall accuracy of ~76% but could have been better if the training data went k > n folds Cross-Validation.


