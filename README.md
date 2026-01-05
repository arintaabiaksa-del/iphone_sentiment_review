# iphone_sentiment_review
End-to-end sentiment analysis of Amazon iPhone reviews using NLP techniques and Machine Learning classification.
# Amazon & App Store Review Sentiment Analysis: iPhone Products

This project focuses on **Natural Language Processing (NLP)** to classify user reviews of iPhone products. By analyzing customer feedback, this project distinguishes between positive and negative sentiments, providing insights into user satisfaction and product performance.

## 🚀 Features
- **Data Scraping:** Integrated tools to fetch real-world review data.
- **Text Preprocessing:** Comprehensive cleaning using `NLTK`, including tokenization and stopword removal.
- **Vectorization:** Implemented `TF-IDF Vectorizer` to convert text into meaningful numerical features.
- **Machine Learning:** Utilized the `Multinomial Naive Bayes` classifier, known for its efficiency in text classification tasks.
- **Prediction:** Includes a pipeline to predict sentiment on new, unseen review data.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `Pandas` & `NumPy` (Data Manipulation)
  - `Scikit-Learn` (Machine Learning & TF-IDF)
  - `NLTK` (Natural Language Toolkit)
  - `Matplotlib` & `Seaborn` (Data Visualization)
- **Environment:** Google Colab

## 📊 Methodology
1. **Exploratory Data Analysis (EDA):** Visualizing distribution of sentiments and review lengths.
2. **Text Cleaning:** Removing special characters, numbers, and common English stopwords to focus on core sentiment-bearing words.
3. **Feature Engineering:** Transforming raw text into a matrix of TF-IDF features to capture word importance.
4. **Model Training:** Training the MultinomialNB classifier on the preprocessed dataset.
5. **Evaluation:** Assessing model performance based on accuracy and prediction consistency.

## 📈 Visualizations
*(Note: Upload your chart images to an 'images' folder in this repo, then update the links below)*

### Sentiment Distribution
![Sentiment Distribution](images/sentiment_dist.png)

### Word Cloud
![Word Cloud](images/wordcloud.png)

## 📝 Performance Result
The model successfully predicts sentiments with high confidence. For example, it correctly identifies "The battery life is amazing" as **Positive (1)** and "The design feels outdated" as **Negative (0)**.

---
*Created as part of my Data Science Portfolio.*
