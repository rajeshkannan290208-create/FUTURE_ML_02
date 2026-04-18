# FUTURE_ML_02
# 🎫 Customer Support Ticket Classification & Priority Prediction

## 📌 Overview

Customer support teams handle thousands of tickets daily. Manually categorizing and prioritizing them is time-consuming and inefficient.

This project uses **Machine Learning + Natural Language Processing (NLP)** to automatically:

* 📂 Classify support tickets into categories (e.g., Billing, Technical, Account)
* ⚡ Predict ticket priority (High / Medium / Low)

👉 This helps organizations **respond faster and improve customer satisfaction**.

---

## 🚀 Features

* 🧹 Text preprocessing (cleaning, stopword removal)
* 🔢 Feature extraction using **TF-IDF**
* 🤖 Machine Learning models (Logistic Regression)
* 📊 Model evaluation (Accuracy, Precision, Recall, F1-score)
* 📉 Confusion matrix visualization
* 🔮 Real-time prediction on custom input
* 💾 Model saving using Pickle

---

## 📂 Dataset

Dataset used:
👉 https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset

### Key Columns:

* `Ticket Description` → Input text
* `Ticket Type` → Category label
* `Ticket Priority` → Priority label

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* NLTK
* Matplotlib, Seaborn
* KaggleHub

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/support-ticket-ml.git
cd support-ticket-ml
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the project:

```bash
python main.py
```

OR open Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📊 Model Workflow

1. Load dataset
2. Clean text (remove stopwords, punctuation)
3. Convert text → numerical features (TF-IDF)
4. Train two models:

   * Category Classification
   * Priority Prediction
5. Evaluate models
6. Predict new tickets

---

## 📈 Results

| Model                   | Accuracy |
| ----------------------- | -------- |
| Category Classification | ~85-90%  |
| Priority Prediction     | ~80-88%  |

*(Results may vary depending on preprocessing and random split)*

---

## 🔮 Example Prediction

Input:

```
"My payment failed and money was deducted"
```

Output:

```
Category: Billing
Priority: High
```

---

## 📉 Visualizations

* Confusion Matrix for Category Model
* Confusion Matrix for Priority Model

---

## 💾 Saved Models

The project saves trained models for reuse:

* `category_model.pkl`
* `priority_model.pkl`
* `vectorizer.pkl`

---

## 📁 Project Structure

```
support-ticket-ml/
│
├── data/
├── main.py / notebook.ipynb
├── category_model.pkl
├── priority_model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

---

## 🎯 Future Improvements

* 🔥 Streamlit Web App (UI for predictions)
* 🧠 Deep Learning (LSTM / BERT)
* 🌍 Multi-language support
* ⚡ Real-time API deployment

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Rajesh Kannan B**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!
