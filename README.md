# 🤖 CODSOFT Machine Learning Internship

This repository contains the projects I completed as part of my **CODSOFT Machine Learning Internship**.  
I successfully implemented **3 tasks** using Python, Scikit-learn, and common ML techniques.

---

## 📂 Tasks Completed

### ✅ Task 1: Movie Genre Classification
- **Goal:** Predict the genre of a movie from its plot summary.
- **Dataset:** [IMDB Genre Classification Dataset](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)
- **Approach:**
  - Preprocessed movie plots.
  - Converted text into **TF-IDF features**.
  - Trained a **Logistic Regression classifier**.
- **Results:** Achieved ~80% accuracy on test data.
- **Sample Prediction:**
  - *"A group of astronauts travel through a wormhole in search of a new home for humanity." → Predicted Genre: Sci-Fi*

📄 Code: [`movie_genre_classification.py`](./movie_genre_classification.py)

---

### ✅ Task 2: Customer Churn Prediction
- **Goal:** Predict whether a customer will churn (leave the service).
- **Dataset:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Approach:**
  - Encoded categorical variables.
  - Standardized numerical features.
  - Trained a **Random Forest Classifier**.
- **Results:** Achieved ~82–85% accuracy.
- **Sample Prediction:** The model correctly identifies whether a customer is likely to churn.

📄 Code: [`customer_churn_prediction.py`](./customer_churn_prediction.py)

---

### ✅ Task 3: Spam SMS Detection
- **Goal:** Classify SMS messages as **Spam** or **Ham (Not Spam)**.
- **Dataset:** [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Approach:**
  - Preprocessed SMS messages.
  - Extracted text features using **TF-IDF**.
  - Trained a **Naive Bayes classifier**.
- **Results:** Achieved ~97% accuracy.
- **Sample Prediction:**
  - *"Congratulations! You’ve won a free iPhone. Claim your prize now!" → Spam*
  - *"Hi, are we still meeting for lunch tomorrow?" → Ham*

📄 Code: [`spam_sms_detection.py`](./spam_sms_detection.py)

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- NumPy  
- Matplotlib / Seaborn (for optional visualization)

---

