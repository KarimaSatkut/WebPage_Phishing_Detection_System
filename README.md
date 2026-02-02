# 🛡️ Web Page Phishing Detection using Machine Learning

## 📌 Project Overview

This project is a Machine Learning-based system designed to detect whether a web page is **Legitimate** or **Phishing** using URL-based features.
Phishing web pages imitate real websites to steal user credentials and financial information.
Our system uses a trained Random Forest classifier and provides real-time predictions through a Streamlit web application.

---

## 🎯 Objectives

* To classify web pages as **Phishing** or **Legitimate** using Machine Learning.
* To analyze URL-based features that indicate suspicious behavior.
* To build a simple MVP (Minimum Viable Product) for real-time prediction.
* To increase cybersecurity awareness among users.

---

## 📊 Dataset

* The dataset contains thousands of web page records with numerical features extracted from URLs.
* Each record is labeled as:

  * `0` → Legitimate
  * `1` → Phishing
* Dataset source: Public phishing datasets (Kaggle / PhishTank / UCI ML Repository).

---

## 🔍 Features Used

Some important features used in the model include:

* URL length
* Number of dots in URL
* Presence of `@` symbol
* HTTPS availability
* Domain age
* Special characters in URL

These features act as indicators of phishing behavior.

---

## ⚙️ Machine Learning Approach

1. Load and preprocess the dataset.
2. Separate features and target labels.
3. Split data into training and testing sets.
4. Train a Random Forest classifier.
5. Evaluate model accuracy.
6. Save the trained model.
7. Deploy the model using Streamlit for real-time prediction.

---

## 🧠 Algorithm Used

* **Random Forest Classifier**

  * Combines multiple Decision Trees for higher accuracy.
  * Reduces overfitting.
  * Works well with structured numerical data.
  * Suitable for cybersecurity classification problems.

---

## 🧪 Model Performance

* Achieved approximately **96% accuracy** on test data.
* Model evaluation performed using accuracy metric and probability thresholds.

---

## 🖥️ Web Application (MVP)

The Streamlit application allows users to input website-related features and predicts:

* ✅ Legitimate Website
* ⚠️ Phishing Website

The application also displays prediction confidence (probability).

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Streamlit
* Joblib
* Machine Learning
* Random Forest Algorithm

---

## 📂 Project Structure

```
├── dataset_B_05_2020.csv
├── train_model.py
├── app.py
├── model.pkl
├── features.pkl
├── accuracy.pkl
└── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/phishing-detection-ml.git
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

(Or manually install)

```bash
pip install pandas scikit-learn streamlit joblib
```

### 3️⃣ Train the model

```bash
python train_model.py
```

### 4️⃣ Run the web application

```bash
streamlit run app.py
```

---

## 🌍 Real-World Applications

* Web browsers
* Email spam filters
* Banking and financial applications
* Corporate security systems
* Cybersecurity awareness tools

---

## 🚀 Future Scope

* Automatic URL input and feature extraction.
* Integration with WHOIS and DNS services.
* Browser extension implementation.
* Deep learning-based phishing detection.
* Web page content and image analysis.

---

## 🤖 AI Tools Usage

ChatGPT was used to assist in understanding machine learning concepts and structuring documentation.
Final implementation and interpretation were done independently.

---

## 📜 License

This project is for educational purposes only.

---

## 👩‍💻 Author

**Karima Satkut**
Data Science Student



Just reply with:
**requirements / description / tags / all**
