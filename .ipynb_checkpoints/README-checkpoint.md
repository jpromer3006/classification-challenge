# classification-challenge
spam_detector

In this challenge, I'm tryin to improve the email filtering for customers experiencing issues with spam emails. I explored two models' performances for spam detection and email classification. I processed/cleaned data, trained and evaluated two machine learning models on a dataset containing email messages that have not been labeled as either spam or non-spam. The goal was to determine which model performed better and why.

Dataset Description
-------------------

The dataset contains 4601 rows & 58 columns, where each message represents spam or not spam.  

Experimental Design
--------------------
Logistic Regression Model
Random Forest Classifier Model

The features were extracted into a Dataframe label X and label Y email (spam),
which was split, scaled then fitted to be used to train and evaluate the two machine learning models.

Results and Discussion
---------------------

Comparing the performance of the two moedels shows that one model had a greater accuracy score than the other without changing anything to the cleaning process. This shows there isn't a one size fits all approach to selecting models for data.

Conclusion
----------

In conclusion, this challenge explored the impact of feature selection and model complexity on performance for spam
email classification tasks. Our results show that both feature selection and model complexity adjustment are important
for improving the performance of machine learning models.  In this case the Random Forest Classifier begins better for classifying data with multidimensional features allowing for better accuracy.  The results confirm a slight margin between the two models making it them both a good tool for classifying spam.  With further fine-tuning both the models should be able to do a consist filtering of spam email.  Thank you
