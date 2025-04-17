# 🧠 Fake Job Post Detection Using NLP

## 👨‍💻 Presented by:
- **SAGIREDDY LAVA KUMAR** – 21B21A4286  
- **CHODAGIRI SRINIVAS** – 21B21A4277  
- **R. SRI CHARAN** – 21B21A42B7  
- **B. SIVA RAMA RAJU** – 21B21A42B1  
- **G. CHANDRA SHEKAR** – 21B21A4287  
- **Guided by:** Ms. Gedela Anitha Rani, M.Tech, Assistant Professor  
- **Institute:** Kakinada Institute of Engineering & Technology – Department of CSE (AI & ML)

---

## 📌 Abstract

This project detects fraudulent job advertisements using Natural Language Processing (NLP) techniques. It leverages TF-IDF for feature extraction and trains a Random Forest classifier to classify job listings as **real** or **fake**. The model is integrated into a Flask-based web application for real-time predictions.

---

## 📊 Dataset

- **Source:** [Kaggle - Fake Job Postings](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)
- **Size:** 18,000+ job posts
- **Classes:**
  - `0` → Real
  - `1` → Fake
- **Key Features:** Job Title, Location, Company Profile, Description, Requirements, Benefits, Telecommuting, Screening Questions, etc.

---

## 🛠️ Technologies & Libraries

- **Languages:** Python  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `Flask`, `pickle`, `os`  
- **ML Model:** Random Forest Classifier  
- **NLP:** TF-IDF Vectorization for text processing

---

## ⚙️ Implementation Steps

1. **Data Preprocessing:**  
   Clean textual fields, remove stopwords/special characters, lemmatize text.

2. **Feature Extraction:**  
   Apply TF-IDF to convert job description and requirements into numerical vectors.

3. **Model Building:**  
   Train a Random Forest Classifier with `class_weight='balanced'` to address class imbalance.

4. **Web Integration:**  
   A Flask-based interface to input job details and get prediction in real-time.

5. **Evaluation:**  
   Accuracy, Precision, Recall, F1-Score used to evaluate model performance.

---

## 📈 Evaluation Metrics

- **Accuracy** – Overall correctness of the model  
- **Precision** – Correctness of positive (fake) predictions  
- **Recall** – Ability to find all actual fake posts  
- **F1-Score** – Balance between precision and recall

---

## 🖥️ Application Use-Cases

- 🔐 Job portal fraud detection (LinkedIn, Indeed, Glassdoor)
- ⚠️ Real-time alerts for suspicious listings
- 🧠 NLP-based browser plugins or extensions
- 🕵️ Government/law enforcement scam tracking
- 🛡️ Company brand protection
- 📬 Email/DM fake job filters

---

## 🚀 Future Scope

- Integrate Deep Learning models (e.g., LSTM, BERT)
- Include more features like job salary, location, etc.
- Mobile/web extension support
- Real-time deployment in job portal APIs
- Use larger, multilingual datasets

---

## 📎 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)  
- [Project GitHub Repository](https://github.com/sindhubhattarai/Capstone-Project)  
- Research papers on NLP + ML-based fake job detection

---

## 🧪 Sample Output

> **Input:** Job title, description, requirements  
> **Output:** `Prediction: FAKE` / `Prediction: REAL` via Flask web interface

---

## 📷 Model Architecture

The model uses a TF-IDF + Random Forest pipeline, with integrated preprocessing and vectorization. A simple frontend takes input text and displays predictions.

---

Feel free to clone, contribute or modify this project for academic or research purposes.
