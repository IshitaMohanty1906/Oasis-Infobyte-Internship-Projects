
# 📧 Email Spam Detection using Machine Learning

## 📝 Overview
This project builds a machine learning model to classify emails (or SMS) as **spam** or **not spam (ham)** using Python. The model uses natural language processing (NLP) techniques and the Naive Bayes algorithm to detect patterns in text data.

---

## 🎯 Objective
To train a classifier using labeled email/SMS data that can distinguish between spam and ham messages with high accuracy.

---

## 🔧 Technologies Used
- Python
- Pandas
- Scikit-learn
- NumPy
- CountVectorizer
- Naive Bayes Classifier
- Matplotlib / Seaborn (for visualization)

---

## 📂 Dataset
We use the **SMS Spam Collection Dataset** from UCI/Kaggle.

📥 Download Link: [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## 🚀 Steps to Run the Project

1. Clone this repository or download the ZIP.
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook email_spam_detection.ipynb
   ```
4. Explore the model and test it with your own inputs!

---

## 📈 Model Accuracy
Our model (Multinomial Naive Bayes) achieves accuracy >95% on test data. It performs well in detecting spam content with minimal false positives.

---

## 📬 Example
```python
sample = ["Congratulations! You've won a free iPhone. Click here to claim."]
prediction = model.predict(cv.transform(sample))
print(prediction)  # Output: [1] -> Spam
```

---

## 📄 License
Open-source project for educational purposes.
