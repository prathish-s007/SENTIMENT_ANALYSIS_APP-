#  Product Review Sentiment Analysis

## Overview

Product Review Sentiment Analysis is a Streamlit-based web application that analyzes customer reviews from PDF files. The application extracts review text, performs sentiment analysis using TextBlob, and visualizes the results through interactive charts and summary statistics.

This project helps users understand customer opinions by classifying reviews into Positive, Negative, and Neutral categories.

---

## ✨ Features

- 📄 Upload PDF files containing product reviews
- 🔍 Automatic text extraction from PDF documents
- ✂️ Review separation using blank-line detection
- 🧠 Sentiment analysis using TextBlob
- 📊 Interactive Pie Chart for sentiment distribution
- 📈 Bar Chart showing sentiment counts
- 📉 Histogram of polarity scores
- 📋 Summary metrics with percentages
- 🔎 Filter reviews by sentiment category
- 📄 View complete review details
- ⬇️ Download sentiment results as CSV

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- TextBlob
- Plotly Express
- PyPDF2
- Regular Expressions (Regex)

---

## 📂 Project Structure

```text
product-review-sentiment-analysis/
│
├── app.py
├── requirements.txt
├── README.md
└── sample_reviews.pdf
```

---

## ⚙️ Installation


### 1. Install Required Libraries

```bash
pip install streamlit pandas textblob plotly PyPDF2
```

### 2. Download TextBlob Corpora

```bash
python -m textblob.download_corpora
```

### 3. Run the Application

```bash
streamlit run app.py
```

---

## 🚀 How to Use

1. Upload a PDF file containing product reviews.
2. Wait for the application to process the file.
3. View sentiment analysis results.
4. Explore charts and summary metrics.
5. Filter reviews by sentiment category.
6. Select a Review ID to view the complete review.
7. Download the results as a CSV file.

---

## 📊 Output Features

### Sentiment Classification
- Positive Reviews
- Negative Reviews
- Neutral Reviews

### Visualizations
- Sentiment Distribution Pie Chart
- Sentiment Count Bar Chart
- Polarity Score Histogram

### Metrics
- Total Positive Reviews
- Total Negative Reviews
- Total Neutral Reviews
- Sentiment Percentage Distribution

---



## 🔮 Future Enhancements

- OCR support for scanned PDFs
- Machine Learning based sentiment analysis
- Multi-language sentiment detection
- Word Cloud visualization
- Database integration
- User authentication system
- Advanced NLP models

---

## 🎯 Applications

- Product Review Analysis
- Customer Feedback Monitoring
- E-commerce Analytics
- Market Research
- Brand Reputation Analysis
- Consumer Opinion Mining

---

## 👨‍💻 Author

**PRATHISH S**

---

## 📜 License

This project is developed for educational and learning purposes.
