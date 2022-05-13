# credit_card_defalut_prediction

We are all aware what is credit card. It is type of payment card in which charges are made against a line of credit instead of the account holder's cash deposits. When someone uses a credit card to make a purchase, that person's account accrues a balance that must be paid off each month. 

Credit card default happens when you have become severely delinquent on your credit card payments. Missing credit card a payment once or twice does not count as a default. A payment default occurs when you fail to pay the Minimum Amount Due on the credit card for a few consecutive months.

Objective of our project is to predict which customer might default in upcoming months. 
We have to build models which help us to predict the defaulters. 

I have applied various Classification Models in our Credit-Card-Default-Prediction such as follows:-
1. Logistic Regression (with Cross Validation)
2. Random Forest Classifier (with Cross Validation)
3. XG Boosting (with Cross Validation)
4. Support Vector Classifier 
5. K-Neighbor Classifier (with Cross Validation) 
6. Gaussian Naïve Bayes Classifier

Some insights:-
1.	There are some features which is having negative correlation like “Age” and “Marriage”

2.	Top 3 models are Random Forest, KNeighbor Classifier and Support Vector Classifier that gives best Presision, Recall, ROC_AUC and F1 score. 

3.	Random Forest Classifier performs best among all models.

4.	Logistic Regression and Gaussian Naive Bayes Classifier is not giving best precision score.

5.	We have found the proportion of defaulters with respect to Marriage, Education, Sex feature and we found that :
  *          Most of the defaulters are Female
  *          Most of the defaulters are from university 
  *          Marital status is Single 
  *          More no. of defaulters are Single

