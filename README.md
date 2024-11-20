### Sentiment Analysis on Restaurant Reviews

This project implements a **Sentiment Analysis** model to classify restaurant reviews as either positive or negative. The dataset consists of 1,000 reviews, with corresponding sentiment labels. The project involves preprocessing text data, creating a Bag-of-Words model for feature extraction, and training a machine learning model to predict sentiments.

#### Key Steps:
1. **Text Preprocessing**:
   - Cleaned reviews by removing special characters, converting to lowercase, and stemming words to their root forms.
   - Removed common stopwords (excluding "not" for preserving sentiment meaning).
   - Prepared a `corpus` of processed reviews for analysis.

2. **Feature Extraction**:
   - Used a **Bag-of-Words model** with the top 1,500 most frequent words as features.
   - Created a sparse matrix representation of the reviews for machine learning.

3. **Model Training**:
   - Trained a **Gaussian Naive Bayes classifier** to learn from the review data.
   - Split the data into training and test sets (80-20 ratio) to evaluate performance.

4. **Evaluation**:
   - Assessed the model using a **confusion matrix** and calculated **accuracy** to measure its effectiveness in classifying sentiments.

#### Technologies Used:
- **Python** for implementation.
- **Natural Language Toolkit (nltk)** for text preprocessing.
- **scikit-learn** for feature extraction and model training.

#### Outcome:
The project demonstrates a simple yet effective approach to sentiment analysis using machine learning. It highlights the importance of text preprocessing, feature engineering, and evaluation metrics in building classification models.
