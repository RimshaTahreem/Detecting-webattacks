# 🚨 Detecting Web Attacks with End-to-End Deep Learning

This project builds an intelligent deep learning-based system to detect web-based attacks and compare it with traditional machine learning models. It includes a secure login system using **Gmail-based OTP verification** for enhanced access control.

---

## 🎯 Objective

To show how deep learning models like **Autoencoders** and **Extension LSTM** can improve the detection of web attacks compared to traditional ML methods such as **SVM** and **Naive Bayes**, based on evaluation metrics like **accuracy, precision, recall, and F1-score**.

---

## 🔒 Secure Login Feature

- Integrated **OTP-based login** system using Gmail verification.
- Ensures that only authorized users can access the application.
- Built-in validation to handle incorrect or expired OTPs.

---

## 📚 Background

Web attacks are increasing in frequency and complexity. Traditional models often fail to adapt to these evolving threats. Our system uses **deep learning** to automatically learn from patterns in web requests and detect attacks with higher accuracy.

We compare performance between:
- ✅ Traditional ML: SVM and Naive Bayes  
- ✅ Deep Learning: Autoencoder and Extension LSTM

---

## 🛠️ Tech Stack

- **Languages**: Python  
- **Libraries**: TensorFlow, Scikit-learn, Pandas, NumPy, Matplotlib  
- **NLP Tools**: NLTK  

---

## 📁 Dataset

- The dataset is **uploaded in this repository**.

---

## 🔍 Models Implemented

| Model Type        | Algorithms Used       | Purpose                             |
|-------------------|------------------------|-------------------------------------|
| Traditional ML    | SVM, Naive Bayes       | Baseline models for comparison      |
| Deep Learning     | Autoencoder, Extension LSTM | Advanced feature learning and detection |

---

## 📊 Evaluation Metrics

Instead of a confusion matrix, we use and visualize the following metrics for all models:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

Each model's results are clearly plotted using bar graphs and performance comparison charts.

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone : https://github.com/RimshaTahreem/Detecting-webattacks
2.**Install dependencies**
pip install -r requirements.txt
3.Run the file
