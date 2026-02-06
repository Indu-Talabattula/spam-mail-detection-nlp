
# Spam Message Detection using NLP

## 📌 Overview
This project implements a Spam Message Detection system using Natural Language Processing (NLP) and Machine Learning techniques. The model classifies messages as **spam** or **ham (not spam)** based on their textual content.

---

## 📊 Dataset
- **SMS Spam Collection Dataset**
- Total messages: **5,574**
- Labels: `spam`, `ham`

---

## 🛠 Technologies Used
- Python
- NumPy, Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Naive Bayes

---

## 🔄 Project Workflow
1. Data loading and preprocessing  
2. Text cleaning and transformation  
3. Feature extraction using **TF-IDF**
4. Model training using:
   - Logistic Regression
   - Naive Bayes
5. Model evaluation and comparison
6. Prediction on custom input messages  

---

## 📈 Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|------|---------|-----------|--------|----------|
| Logistic Regression | 96.68% | 96.29% | 100% | 98.11% |
| Naive Bayes | **97.31%** | **96.97%** | **100%** | **98.46%** |

---

## 🧾 Confusion Matrix (Logistic Regression)

[[118 37]
[ 0 960]]


- No spam messages were missed (Recall = 1.0)
- 37 ham messages were incorrectly classified as spam

---

## 🧠 Key Observations
- Both models achieved **perfect recall**, ensuring no spam messages were missed.
- **Naive Bayes outperformed Logistic Regression** with higher accuracy, precision, and F1-score.
- Naive Bayes proved to be more effective and computationally efficient for text-based spam detection.

---

## 🧪 Sample Prediction
The trained model can predict whether a given message is spam or ham using real-time input text.

---

## 🔮 Future Enhancements
- Extend the system to **email spam detection** using the Enron dataset
- Experiment with **SVM and Deep Learning models**
- Deploy the model as a **web application**

---

## 📌 Conclusion
This project demonstrates the effectiveness of NLP and machine learning techniques in spam detection. Comparing multiple models helped identify Naive Bayes as the most suitable algorithm for this task.

