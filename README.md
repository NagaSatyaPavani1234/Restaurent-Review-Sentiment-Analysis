# 🍽️ Restaurant Review Sentiment Analysis using NLP

## 📌 Project Overview

This project performs **Sentiment Analysis on Restaurant Reviews** using Natural Language Processing (NLP) techniques.

The project analyzes customer reviews and classifies them into three sentiment categories:

- 😊 **Positive**
- 😐 **Neutral**
- 😞 **Negative**

The objective is to understand customer opinions and identify the overall sentiment expressed in restaurant reviews.

---

## 🎯 Aim

The aim of this project is to perform sentiment analysis on restaurant reviews using **Natural Language Processing (NLP)** techniques.

The system classifies customer reviews into Positive, Negative, or Neutral categories based on the sentiment expressed in the review text.

---

## 📊 Dataset

The dataset used in this project is:

`restaurant_reviews.csv`

It contains textual reviews provided by customers about their restaurant experiences.

Each record represents a customer review describing their experience.

Before processing, the dataset was checked for:

- Missing values
- Duplicate records
- Unnecessary characters

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NLTK**
- **TextBlob**
- **Matplotlib**
- **Google Colab**

These tools were used for text preprocessing, sentiment polarity calculation, analysis, and visualization.

---

## 🔄 Methodology

The project follows these steps:

### 1. Import Required Libraries

Required Python libraries such as Pandas, NLTK, TextBlob, and Matplotlib were imported.

### 2. Load the Dataset

The restaurant review dataset was loaded using Pandas.

### 3. Data Cleaning

The dataset was cleaned by:

- Removing duplicate records
- Removing unnecessary characters
- Checking the dataset for missing values

### 4. Text Preprocessing

The review text was prepared for analysis by:

- Converting text into lowercase
- Removing stopwords
- Cleaning unnecessary characters

### 5. Sentiment Polarity

**TextBlob** was used to calculate the sentiment polarity of each restaurant review.

### 6. Sentiment Classification

Based on the sentiment polarity, reviews were classified into:

- **Positive**
- **Neutral**
- **Negative**

### 7. Visualization

Visualizations were generated to understand the distribution of sentiments across the restaurant reviews.

---

## 📈 Data Analysis & Visualizations

### 📊 Sentiment Distribution Bar Chart

A bar chart was created to show the number of:

- Positive reviews
- Negative reviews
- Neutral reviews

This helps understand the overall sentiment distribution in the dataset.

### 📉 Sentiment Score Histogram

A histogram was created to show the distribution of sentiment polarity scores across the restaurant reviews.

---

## 🔍 Observations

The analysis produced the following observations:

- Most reviews were **Positive**, indicating good customer satisfaction.
- Some reviews were **Neutral**, representing mixed or moderate experiences.
- A smaller number of reviews were **Negative**, highlighting areas where customer experiences could be improved.

---

## 💡 Conclusion

Sentiment analysis was successfully performed on restaurant reviews using **Natural Language Processing techniques**.

Text preprocessing helped prepare the review data, while **TextBlob sentiment polarity** was used to classify the reviews into Positive, Neutral, and Negative categories.

This project demonstrates how **NLP and sentiment analysis can be used to analyze customer feedback and support decision-making**.

---

## 📁 Project Structure

```text
Restaurant-Review-Sentiment-Analysis/
│
├── restaurant_reviews.csv
├── Restaurant_Review_Sentiment_Analysis.ipynb
├── Restaurant_Review_Sentiment_Analysis_Report.pdf
└── README.md
