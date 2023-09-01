# Sentiment Analysis Mini Project (Amazon Customer Reviews)
This mini project aims to classify Amazon product reviews into distinct sentiment categories: Positive, Neutral, and Negative. The machine learning model is trained on a dataset containing Amazon customer reviews along with their star ratings.

Methodology-- <br/>
Data Preprocessing: The text data is cleaned to remove any irrelevant characters. <br/>
Feature Engineering: TF-IDF (Term Frequency-Inverse Document Frequency) is used for text vectorization. <br/>
Handling Class Imbalance: Random oversampling is applied to balance the classes. <br/>
Modeling: Hyperparamater tuning and CV is used to develop a Logistic Regression model to classify the reviews into their respective sentiment categories.
