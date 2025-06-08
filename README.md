# 🧠 Sentiment Analysis Web Application

This project is a **Sentiment Analysis** system built using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The application analyzes customer reviews and classifies them as **Positive** or **Negative**. It includes a simple web interface where users can enter their product feedback, and the system dynamically keeps track of the number of positive and negative reviews.

---

## 💡 Project Overview

- 📝 **Input**: A product review (entered via a web form)
- ⚙️ **Processing**:
  - Text preprocessing
  - Feature vectorization
  - Sentiment prediction using a trained ML model
- 📊 **Output**:
  - Classification of the review: **Positive** or **Negative**
  - Count of all positive and negative reviews submitted
  - Source of each feedback stored for reference

---

## 🚀 Features

- Simple and intuitive **Flask based web interface**
- Real time sentiment prediction (positive/negative)
- Feedback count tracking

---

## 🧪 How It Works

- Enter a product review in the text box.
- Click Submit.
- The system::
  - Preprocesses the input
  - Converts text into vectors.
  - Predicts sentiment.
- Displays:
  - Whether the review is positive or negative
  - Updated count of all review sentiments

---

## 🛠 To Run 

```
python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

python app.py
```



