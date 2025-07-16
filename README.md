# ANALYSIS-ON-SENTIMENTAL-DATA-USING-SOCIAL-MEDIA
Analysis on Sentimental Data Using Social Media" is a data science and natural language processing (NLP) project that focuses on extracting and analyzing sentiments from user-generated content on social media platforms like Twitter. 


# 😊 Analysis on Sentimental Data Using Social Media

This project focuses on analyzing sentiment from social media posts using Natural Language Processing (NLP) techniques. The aim is to classify the sentiment expressed in user-generated content as **positive**, **negative**, or **neutral**, and visualize the overall emotional tone of a social media dataset.

---

## 📌 Objective

- To extract and clean textual data from social media platforms.
- To perform sentiment classification using NLP techniques and machine learning.
- To visualize public opinion trends using charts and word clouds.

---

## 🗂️ Dataset

- **Source:** [Kaggle Twitter Sentiment Dataset](https://www.kaggle.com/kazanova/sentiment140) 
- **Format:** CSV
- **Fields:** Tweet ID, Date, Username, Text, Sentiment Label

---

## 🧠 Techniques Used

- Text Preprocessing (Tokenization, Lemmatization, Stopword Removal)
- Sentiment Classification
- Word Frequency Analysis
- Data Visualization

---

## ⚙️ Tools & Technologies

- Python
- Pandas, NumPy
- NLTK, Scikit-learn, TextBlob, VaderSentiment
- Matplotlib, Seaborn, WordCloud
- Jupyter Notebook / Google Colab

---

## 🔄 Project Workflow

1. **Data Loading**
   - Load CSV dataset into pandas dataframe

2. **Data Preprocessing**
   - Lowercasing
   - Removing special characters, URLs, mentions, hashtags
   - Stopword removal
   - Lemmatization

3. **Sentiment Analysis**
   - Using `TextBlob` or `VaderSentiment`
   - Optional: Train ML models (Naive Bayes, Logistic Regression, etc.)

4. **Visualization**
   - Word Cloud for most common words
   - Pie/Bar chart for sentiment distribution
   - Time series analysis (if data includes timestamp)

---

## 📊 Sample Visuals

### 📈 Sentiment Distribution
![Sentiment Chart](images/sentiment_distribution.png)

### ☁️ Word Cloud (Positive Tweets)
![Word Cloud](images/wordcloud_positive.png)

---

## 📁 Directory Structure

