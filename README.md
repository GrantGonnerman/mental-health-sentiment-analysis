# Mental Health Sentiment Analysis

**Natural Language Processing (NLP) Project** | Analyzing sentiment in mental health-related text data to support mental wellness insights.

## 📋 Project Overview
This project applies NLP techniques and machine learning models to perform sentiment analysis on mental health-related text (such as social media posts, forum discussions, or survey responses). The goal is to classify text as positive, negative, or neutral to better understand emotional states and identify potential mental health concerns.

## 🎯 Business / Real-World Impact
Mental health awareness is increasingly important. Automated sentiment analysis can help organizations, helplines, and researchers detect negative sentiment at scale, enabling earlier support and intervention for individuals in distress.

## 🗂️ Dataset
- **Source**: Mental health text dataset (loaded from AWS S3)
- **Target**: Sentiment classification (Positive, Negative, Neutral)
- **Features**: Raw text data from mental health discussions, posts, or responses

## 🔧 Key Techniques & Models
- **Text Preprocessing**: Cleaning, tokenization, stopword removal, lemmatization
- **Exploratory Data Analysis**: Word clouds, sentiment distribution, and common term analysis
- **Feature Engineering**: TF-IDF vectorization, possibly word embeddings
- **Modeling**:
  - Traditional ML classifiers (Logistic Regression, Random Forest, etc.)
  - Advanced models (XGBoost, LightGBM)
  - Potential deep learning approaches (if used)
- **Evaluation**: Accuracy, Precision, Recall, F1-score, and Confusion Matrix

## 📊 Results
- Strong classification performance on mental health sentiment
- Identified key linguistic patterns associated with negative sentiment
- Demonstrated practical application of NLP in a socially impactful domain

## 📄 Reports
- [Full Project Report (PDF)](Mental%20Health%20Sentiment%20Analysis/Reports/Mental%20Health%20Sentiment%20Analysis%20Report.pdf)
- [Presentation Slides (PDF)](Mental%20Health%20Sentiment%20Analysis/Reports/Mental%20Health%20Sentiment%20Analysis%20Slides.pdf)

## 🛠️ Technologies Used
**Python** • **pandas** • **scikit-learn** • **NLTK** / **spaCy** • **TF-IDF** • **XGBoost** • **Matplotlib** • **Seaborn** • **WordCloud**
