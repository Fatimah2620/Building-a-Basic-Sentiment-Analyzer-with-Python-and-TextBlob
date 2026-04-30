أكيد، هذا **README احترافي باللغة الإنجليزية** وجاهز للـ GitHub 👇

---

# 📊 Sentiment Analysis Project

**ARTI 303 – Programming for AI**

## 📌 Project Overview

This project focuses on building a **Sentiment Analysis system** using Python to automatically classify customer reviews into **positive, neutral, or negative sentiments**.

The system was applied to Amazon reviews of the **Samsung Galaxy S4**, analyzing more than 6,000 reviews to extract meaningful insights about customer satisfaction.

> The project follows the course requirements and demonstrates a real-world AI application 

---

## 🎯 Problem Statement

Amazon sellers receive thousands of customer reviews, making manual analysis:

* Time-consuming
* Inefficient
* Prone to human error

The goal is to develop an intelligent system that:

* Automatically classifies reviews
* Summarizes customer opinions
* Supports faster decision-making

---

## 🤖 AI Solution

The solution was implemented using:

* Python
* Pandas
* TextBlob
* Matplotlib

### 🔍 Methodology

Each review is analyzed using **TextBlob polarity scores**, then classified as:

```python
Negative: polarity < -0.2  
Neutral: -0.2 <= polarity <= 0.2  
Positive: polarity > 0.2
```

### 🧠 Implementation

* `sentimentAnalyzer(text)` → Classifies sentiment
* `compute_polarity(text)` → Extracts polarity score
* `SentimentAnalyzer class` → Provides a structured and reusable design

---

## 📂 Dataset

* Source: Amazon Unlocked Mobile Phones Dataset
* Filter applied: **Samsung Galaxy S4 reviews only**

### 📊 Dataset Statistics

* Number of reviews: **6056**
* Number of columns: **7**
* Shortest review length: **2 characters**
* Longest review length: **8188 characters**
* Average review length: **~180 characters**

> Statistics are based on the project report (page 3) 

---

## ⚠️ Data Preprocessing

* Missing values in **Brand, Price, Votes** were ignored (not required)
* Missing review text was replaced with empty strings
* The system handles incomplete data automatically

---

## 📈 Results

### 🔢 Sentiment Distribution

* Positive: **3379**
* Neutral: **2381**
* Negative: **296**

➡️ Most customers expressed **positive sentiment**

---

## 📊 Visualizations

The project includes:

* 📌 Bar chart for sentiment distribution
* 📌 Histogram for polarity values (-1 to +1)

> Visual results are shown in the report (pages 3–4) 

---

## ⚡ Mismatched Reviews Analysis

A total of **214 mismatched cases** were identified where:

* The review rating does not match the predicted sentiment

### Possible Reasons:

* Sarcasm
* Mixed opinions in a single review
* Poor grammar
* Complaints about the seller instead of the product

---

## 💡 Business Value

This system helps sellers to:

* Automatically classify reviews
* Quickly understand customer satisfaction
* Detect recurring issues
* Make data-driven decisions

---

## 🏁 Conclusion

This project successfully demonstrates the practical use of sentiment analysis in real-world scenarios.

* Over 6000 reviews were analyzed
* Valuable insights were generated
* Results indicate high customer satisfaction with some recurring concerns

➡️ The project meets all course requirements and showcases a real AI application


---

## 🚀 How to Run

Install dependencies:

```bash
pip install pandas textblob matplotlib
```

Run the notebook:

```bash
ARTI 303 – Programming for AI.ipynb
```

---

إذا تبغي نسخة **أقوى للـ Portfolio (مع badges + شكل احترافي جدًا)** قولي لي 👍
