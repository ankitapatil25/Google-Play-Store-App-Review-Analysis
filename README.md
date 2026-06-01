# Google-Play-Store-App-Review-Analysis
# 📱 Google Play Store App Review Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Google Play Store applications and user reviews.

The objective is to identify factors affecting application success, user engagement, ratings, installs, and customer sentiment.

The analysis was performed using Python and Google Colab.

---

## 🎯 Business Objective

To analyze application data and answer key business questions such as:

- Which categories are most popular?
- Do ratings influence installs?
- How are reviews related to app success?
- Do free apps perform better than paid apps?
- What insights can be derived from user sentiments?

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📂 Dataset Information

### Play Store Dataset

Contains:

- App Name
- Category
- Rating
- Reviews
- Installs
- Size
- Price
- Type
- Content Rating
- Genres
- Last Updated

### User Reviews Dataset

Contains:

- App
- Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Cleaned Installs column
- Converted Reviews to numeric format
- Standardized Size values
- Cleaned Price column
- Converted date columns
- Merged review and app datasets

---

## 📊 Exploratory Data Analysis

Analysis included:

### Univariate Analysis

- Rating Distribution
- App Category Distribution
- Sentiment Distribution

### Bivariate Analysis

- Installs vs Reviews
- Category vs Ratings
- Type vs Installs

### Multivariate Analysis

- Correlation Heatmap
- Sentiment Analysis
- Category Performance Analysis

---

## 🔍 Key Insights

### 1. Free Applications Dominate

Free applications receive significantly more installs compared to paid applications.

### 2. Installs and Reviews are Highly Correlated

Applications with higher installs generally receive more reviews.

### 3. Positive Sentiment Dominates

Most user reviews are positive, indicating overall customer satisfaction.

### 4. Popular Categories

Categories such as Communication, Tools, Family, and Games contain the largest number of applications.

### 5. High Ratings Improve Visibility

Applications with higher ratings tend to achieve stronger user engagement.

---

## 🚀 Future Improvements

Future enhancements can include:

- Machine Learning Models
- App Success Prediction
- NLP-based Review Analysis
- Interactive Power BI Dashboard
- Recommendation Systems

---

## 👩‍💻 Author

Ankita Patil

B.Tech Computer Engineering

Aspiring Data Analyst
