# FakeNewsDetectionTamil
A data mining project on Fake news detection in Tamil

The aim of this project is to develop a machine learning-based approach for detecting fake news in Tamil language using a dataset of 10 thousand fake news and 40 thousand real news articles scraped from a popular Tamil news website. The project aims to leverage various machine learning algorithms, including Support Vector Machines (SVM), Logistic Regression, Decision Tree, K-Nearest Neighbors (KNN), Random Forest, and Naive Bayes, to train a model that can accurately identify fake news in real-time. The project also involves data preprocessing, including translation of the dataset from Tamil to English using Google Translate, data cleaning, and feature extraction. 

DATASET SOURCE:
•	Real News Dataset – Scraped from One India Website
•	Fake News Dataset – Github Repository

DATA PREPROCESSING:
Preprocessing is an essential step in preparing the dataset for machine learning. In this project, the preprocessing of the translated CSV file containing both English and Tamil news articles involves several natural language processing techniques, including stemming, lemmatization, stopword removal, punctuation removal, and text cleaning.
1.	Stemming: Stemming is the process of reducing words to their root or base form, known as a stem. It helps in reducing variations of words and consolidating similar words. In this project, stemming may be applied to both English and Tamil text to reduce words to their respective stems.
2.	Lemmatization: Lemmatization is the process of reducing words to their canonical or dictionary form, known as a lemma. It helps in obtaining meaningful representations of words. In this project, lemmatization may be applied to both English and Tamil text to obtain their lemmas.
3.	Stopword Removal:Stopwords are commonly occurring words that do not carry significant meaning and can be removed to reduce noise and improve processing efficiency. Examples of stopwords include "the", "and", "is", "in", etc. In this project, stopword removal may be applied to both English and Tamil text to eliminate irrelevant words.
4.	Punctuation Removal: Punctuations are special characters used in text for various purposes, such as sentence separation, emphasis, or abbreviation. In this project, punctuation removal may be applied to both English and Tamil text to eliminate punctuation marks, including commas, periods, exclamation marks, etc.
The combination of these preprocessing techniques helps in standardizing the text data and reducing noise, making it more suitable for machine learning algorithms to learn meaningful patterns and features for fake news detection in Tamil language.
MINING TECHNIQUES USED:
The cleaned data is splitedradomly into two parts - 80% traing and 20% testing dataset, we then use six different machine learning project.
1.	Support Vector Machine (SVM): SVM is a supervised machine learning algorithm used for classification and regression tasks. It finds a hyperplane that best separates the data into different classes, making it suitable for binary or multiclass classification tasks with good generalization performance.
2.	Logistic Regression: Logistic regression is a statistical method used for binary classification tasks. It models the probability of an input belonging to a certain class using a logistic function, making it simple and interpretable, and suitable for problems with linearly separable data.
3.	Decision Tree: Decision tree is a tree-based algorithm used for classification and regression tasks. It recursively splits the data based on feature values, creating a tree-like structure that can be easily visualized and interpreted, making it suitable for problems with non-linear decision boundaries and interactions among features.
4.	k-Nearest Neighbors (KNN): KNN is a simple and intuitive algorithm used for classification tasks. It classifies an input based on the majority class of its k-nearest neighbors in the feature space, making it suitable for problems with local patterns and small datasets.
5.	Random Forest: Random Forest is an ensemble method that combines multiple decision trees to make predictions. It improves the accuracy and robustness of decision trees by reducing overfitting and increasing diversity among trees, making it suitable for complex problems with large datasets.
6.	Naive Bayes: Naive Bayes is a probabilistic algorithm used for classification tasks. It assumes that features are conditionally independent given the class, making it computationally efficient and suitable for problems with large feature spaces and limited data.
These models are trained on the cleaned data to learn patterns and relationships between features. The aggregation all these models allows to make accurate predictions on the classification of news articles as fake or real in Tamil language.

