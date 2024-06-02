# StackOverflow-Tag-Prediction
## Business Problem
### Description
Stack Overflow is the largest, most trusted online community for developers to learn, share their programming knowledge, and build their careers.

Stack Overflow is something which every programmer uses one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming. The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg. As of April 2014, Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000 questions in late August 2015. Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.

Source: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/
### Problem Statement
Given a Title and body of a question, suggest the relevant tags associated with the question.
## Objective & Constraints
1.	Predict as many tags as possible with high a precision and recall.
2.	Incorrect tags could impact customer experience on StackOverflow.
3.	No strict latency constraints.

## Results
 ![image](https://github.com/vermaanuj15/StackOverflow-Tag-Prediction/assets/72166368/284e1acf-2f41-4b39-b960-2b03dd358c6e)

## Conclusion
Here we limited ourselves to simple linear models likes Logistic Regression and Linear SVM. Because we used Count vectorizers and Tf-idf vectorizers and our data is high dimensional, Decision Tree, Random Forest, GBDT would fail to work.
Time Complexity – As we have considered 500 labels, so we have to train 500 models and hence Linear model makes more sense.
