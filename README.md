# 📩 SMS Spam Classification

A Machine Learning project that classifies SMS messages as **Spam 🚨** or **Not Spam (Ham) ✅** using Natural Language Processing (NLP).

---

## 🚀 Project Overview

Spam messages are unwanted messages that often contain advertisements, scams, or phishing links.
This project uses **Machine Learning and NLP techniques** to automatically detect whether an SMS message is spam or not.

The model is trained on an SMS dataset and deployed using **Streamlit** so users can test messages in real time.

---

## 🧠 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Text Preprocessing
5. Feature Extraction using **TF-IDF**
6. Model Training
7. Model Evaluation
8. Deployment with **Streamlit**

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **NLTK**
* **Seaborn / Matplotlib**
* **Streamlit**

---

## 📊 Model Used

The following models were tested:

* Naive Bayes
* Logistic Regression
* Support Vector Machine
* Random Forest

✅ **Best Performing Model:** Multinomial Naive Bayes

---

## 📁 Project Structure

```
sms-spam-classifier
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── spam.csv
├── requirements.txt
├── README.md
└── notebook.ipynb
```

---

## ⚙️ Installation

Clone the repository

```
git clone https://github.com/Devani99/sms_spam_classification.git
```

Move to project folder

```
cd sms-spam-classification
```

Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Run the Streamlit app

```
streamlit run app.py
```

Open the browser at:

```
http://localhost:8501
```

---

## 📸 Example

Input Message:

```
Congratulations! You have won a free iPhone.
```

Output:

```
Spam 🚨
```

---

## 📈 Features

* Text preprocessing with **NLTK**
* TF-IDF vectorization
* Multiple model comparison
* Streamlit interactive interface
* Real-time SMS classification

---

## 🌐 Deployment

This project can be deployed using:

* **Streamlit Cloud**
* **Render**
* **HuggingFace Spaces**
* **Heroku**

---

## 📚 Dataset

The dataset used is the **SMS Spam Collection Dataset**.

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is open source and available under the **MIT License**.

---

## 👨‍💻 Author

Your Name
GitHub: https://github.com/Devani99
