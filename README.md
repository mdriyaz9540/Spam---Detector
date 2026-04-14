# 📩 SMS Spam Classifier (NLP Project)

## 🚀 Live Demo

👉 https://spam---detector-jzwcryrv39xdfybrmuce2z.streamlit.app/

---

## 📌 Project Overview

This project is an **NLP-based SMS Spam Classifier** that predicts whether a message is **Spam 🚫** or **Not Spam ✅**.

The model is trained on a real-world SMS dataset and deployed as a **web application** using Streamlit.

---

## 🎯 Problem Statement

Spam messages are a major issue in communication systems.
This project aims to build a machine learning model that can automatically detect spam messages and filter them out.

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* NLTK (Natural Language Processing)
* Streamlit (for deployment)

---

## ⚙️ Features

* Text preprocessing (cleaning, tokenization, stopword removal, stemming)
* TF-IDF vectorization
* Spam classification using Machine Learning
* Interactive web interface
* Real-time predictions

---

## 🧠 Model Used

* Multinomial Naive Bayes

### Why Naive Bayes?

* Works well with text data
* Fast and efficient
* Performs well for classification tasks

---

## 📊 Model Performance

* Accuracy: ~96%
* Evaluated using Confusion Matrix

---

## 🔄 Workflow

1. Data Cleaning
2. Text Preprocessing
3. Feature Extraction (TF-IDF)
4. Model Training
5. Model Evaluation
6. Deployment using Streamlit

---

## 📂 Project Structure

```
spam-detector/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── notebook.ipynb
```

---

## ▶️ How to Run Locally

1. Clone the repository

```
git clone https://github.com/your-username/spam-detector.git
```

2. Navigate to folder

```
cd spam-detector
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Run the app

```
streamlit run app.py
```

---

## 🌐 Deployment

This project is deployed using **Streamlit Cloud**.

---

## 💡 Future Improvements

* Add more advanced models (Logistic Regression, SVM)
* Improve UI/UX
* Add message confidence score
* Use deep learning (LSTM / BERT)

---

## 🙌 Acknowledgements

* Dataset from Kaggle
* Inspired by NLP classification problems

---

## 📬 Contact

If you have any suggestions or feedback, feel free to connect!

---

⭐ If you like this project, don’t forget to give it a star!
