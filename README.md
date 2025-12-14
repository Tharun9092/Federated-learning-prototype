# 🏥 Federated Learning Prototype for Privacy-Preserving Healthcare Analytics

## 📌 Overview
This repository contains an **academic prototype** that compares **Centralized Machine Learning** and **Federated Learning** approaches for healthcare data analytics.

The objective of this project is to evaluate whether **Federated Learning (FL)** can achieve predictive performance comparable to centralized models **while preserving data privacy** by keeping sensitive patient data local.

The prototype is implemented using a **Jupyter Notebook**, with an accompanying **HTML export** that presents the executed results in a reproducible, read-only format.

---

## 🧠 Models Implemented
The following machine learning models were implemented and evaluated:

- 📈 Logistic Regression  
- 🌲 Random Forest  
- 🧠 Feedforward Neural Network (MLP)

Each model is trained using:
- A **centralized approach** (single combined dataset)
- A **federated approach** (data split across simulated hospital clients)

---

## 🔐 Privacy-Preserving Design
This prototype follows **privacy-by-design principles**:

- 🏥 Data is partitioned to simulate multiple hospitals/clients  
- 🚫 Raw data never leaves the local client  
- 🔄 Only model parameters/updates are shared  
- 📉 Reduces risks of data leakage and regulatory violations  

This design aligns with healthcare privacy requirements and GDPR-oriented constraints.

---

## 📂 Repository Contents
- `prototype.ipynb` → Complete implementation and experiments  
- `prototype.html` → Executed notebook with results (no execution required)  
- `README.md` → Project documentation  

---

## ⚙️ Technologies Used
- 🐍 Python  
- 📊 NumPy, Pandas  
- 🤖 Scikit-learn  
- 🔥 PyTorch  
- 📓 Jupyter Notebook  

---

## ▶️ How to Run the Prototype
1. Open the notebook using Jupyter:
   ```bash
   jupyter notebook prototype.ipynb
   

## 👤 Author
**Tharun Kumar Reddy Chalamala**  
🎓 MSc Student – Human-Centered Artificial Intelligence  
📍 Technological University Dublin  
💡 Interests: Federated Learning, Privacy-Preserving AI, Ethical & Human-Centered AI  
🔧 Skills: Python, Machine Learning, Federated Learning, Data Analysis  

🔗 LinkedIn: https://www.linkedin.com/in/tharun-kumar-reddy-6941a22a6/

