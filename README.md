# 📱 Sentiment Analysis on X App Reviews – Google Play Store

This project analyzes user sentiment from **Google Play Store reviews** of the **X** application using **Natural Language Processing (NLP)** techniques. It aims to classify user reviews into **positive**, **neutral**, and **negative** categories to provide insights into user satisfaction and areas for improvement.

📍 Project Notebook: [`Sentimen_Analisis_Aplikasi_X_Google_Play_Store.ipynb`](./Sentimen_Analisis_Aplikasi_X_Google_Play_Store.ipynb)

---

## 🔍 Objective

- Scrape user reviews from Google Play Store
- Clean and preprocess Indonesian-language text
- Perform sentiment classification using machine learning
- Visualize review distributions, word clouds, and sentiment insights

---

## 📦 Features

- ✅ Google Play Store scraper using `google-play-scraper`
- 🧼 Text preprocessing (cleaning, stemming, stopword removal, slang normalization)
- 📊 Data visualization with `seaborn`, `matplotlib`, and `wordcloud`
- 🤖 Sentiment classification using Logistic Regression
- 📈 Evaluation metrics and confusion matrix

---

## 🧠 Technologies Used

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn, WordCloud
- NLTK, Sastrawi (Indonesian stemmer)
- Scikit-learn
- Google Play Scraper

---

## 🗂️ Folder Structure

```
x-sentiment-analysis/
├── Sentimen_Analisis_Aplikasi_X_Google_Play_Store.ipynb
├── assets/ # Images or wordclouds (optional)
├── README.md # You are here!
```

---

## 🚀 How to Run the Project

1. **Clone this repository**

```
git clone https://github.com/hazhyni/x-sentiment-analysis.git
cd x-sentiment-analysis
```

2. **Install Dependencies**
   
```
pip install -r requirements.txt
# or install manually
pip install google-play-scraper pandas numpy matplotlib seaborn nltk Sastrawi wordcloud requests
```

3. **Run the Notebook**
Open Sentimen_Analisis_Aplikasi_X_Google_Play_Store.ipynb in Jupyter Notebook or Google Colab.


