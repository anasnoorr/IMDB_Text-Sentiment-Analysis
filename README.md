# IMDB_Text-Sentiment-Analysis


# 🧠 Sentiment Analysis on IMDB Movie Overviews
This project builds a sentiment analysis model using IMDB movie overviews to classify each description as positive, negative, or neutral based on its content.

 # 📌 Task Description
The main objective was to implement a machine learning model for sentiment classification, including:

Text Preprocessing: Lowercasing, tokenization, stopword removal, and lemmatization.

Feature Engineering: Text was converted into numerical format using TF-IDF.

Model Training: A Logistic Regression classifier was trained on the cleaned text data.

Model Evaluation: Performance was assessed using precision, recall, and F1-score.

 # 🛠️ Tools & Libraries Used
Pandas, NumPy for data handling

NLTK for natural language preprocessing

TextBlob for sentiment polarity scoring

Scikit-learn for model training and evaluation

 # 📊 Model Performance
The model was evaluated on a holdout test set. Below is a snapshot of its performance:

markdown
Copy
Edit
              precision    recall  f1-score   support

    Negative       0.53      0.62      0.57        66
     Neutral       0.34      0.22      0.27        46
    Positive       0.65      0.68      0.66        88

    accuracy                           0.56       200
   macro avg       0.51      0.51      0.50       200
weighted avg       0.54      0.56      0.54       200


# The model performs best on positive and negative reviews, while neutral sentiment is more challenging to classify — likely due to subtler language cues and fewer samples.
