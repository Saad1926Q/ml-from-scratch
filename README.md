# ML Practice

Welcome to the **ML Practice** repository!

## Contents

### 1. **Car Price Prediction Model**
   - **Objective**: Predict car prices using a dataset containing features such as car name, company, year, price, kilometers driven, and fuel type.
   - **Key Steps**:
     - Data cleaning and preprocessing.
     - Building a linear regression model.
     - Utilizing transformers and pipelines for efficient processing.

### 2. **Spam Detector**
   - **Objective**: Build a spam detection model using natural language processing techniques.
   - **Dataset**: Spam dataset from the UCI Machine Learning Repository.
   - **Key Steps**:
     - **Data Cleaning**:
       - Convert text to lowercase.
       - Tokenization: Break down sentences into words/tokens.
       - Remove special characters, stop words, and punctuation.
       - Perform stemming to reduce words to their root form.
     - **Exploratory Data Analysis (EDA)**:
       - Compare word, character, and sentence counts in spam vs. ham (non-spam) messages using NLTK.
       - Generate a word cloud to visualize frequently occurring words.
     - **Text Vectorization**:
       - Convert text into numerical vectors using techniques like TF-IDF or Bag of Words.
     - **Modeling**:
       - Tried several models:
         - Support Vector Classifier (SVC)
         - K-Nearest Neighbors (KNN)
         - Multinomial Naive Bayes (MNB)
         - Decision Tree Classifier
         - Logistic Regression
         - Random Forest Classifier
         - AdaBoost Classifier
         - Bagging Classifier
         - Extra Trees Classifier
         - Gradient Boosting Classifier
         - XGBoost
     - **Best Model**: Multinomial Naive Bayes (MNB) gave the best result for spam detection.
