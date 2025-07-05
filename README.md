#Spam SMS Classifier using NLTK & Scikit-learn
This project builds a machine learning model to classify SMS messages as spam or ham using Natural Language Processing (NLP) techniques. The dataset is processed using NLTK, and classification is done using various Scikit-learn models.
# Features
Preprocesses raw SMS data: removes punctuation, symbols, numbers, URLs, etc.

Tokenizes and stems text using nltk.

Creates a Bag of Words model using the 1500 most frequent terms.

Trains multiple classifiers:

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Logistic Regression

Implements an ensemble Voting Classifier

Evaluates accuracy and performance with:

Accuracy Score

Confusion Matrix

Classification Report

Dataset used: spam.csv

Contains two main columns:

v1: Label (ham or spam)

v2: SMS text

# Sample Output
bash
Copy
Edit
SVC Accuracy: 98.3%
K Nearest Neighbors Accuracy: 93.0%
Decision Tree Accuracy: 96.4%
Random Forest Accuracy: 97.6%
Logistic Regression Accuracy: 98.4%
Voting Classifier: Accuracy: 98.4%

# Models Used
SVC(kernel='linear')

KNeighborsClassifier()

DecisionTreeClassifier()

RandomForestClassifier()

LogisticRegression()

VotingClassifier() (Ensemble)

# Confusion Matrix Example
kotlin
Copy
Edit
              predicted
               ham  spam
actual ham     1213    5
       spam      15   170

# Evaluation Metrics
Accuracy

Precision / Recall / F1-Score

Confusion Matrix



