# 📝 Resume Analyzer App

A smart, AI-powered application that analyzes resumes, predicts the most relevant job role, and summarizes key details — all through a simple, user-friendly interface.

---

## 🚀 Project Overview

The Resume Analyzer App uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically classify resumes into one of 25 job roles and generate concise summaries of each candidate’s profile.

This tool is designed to help HR teams and recruiters **save time**, **streamline screening**, and make **data-driven hiring decisions**.

---

## 🔍 Key Features

- 📄 **PDF Resume Upload & Parsing**
- 🧠 **Job Role Prediction using ML (92% accuracy)**
- ✍️ **Automatic Resume Summarization**
- ⚡ Fast, responsive interface built with **Streamlit**
- 🔐 Local model loading for quick inference (no API dependencies)

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - `scikit-learn`, `nltk`, `re`, `PyPDF2`, `pickle`, `pandas`  
- **Frameworks:**  
  - `Streamlit` (for the web interface)  
- **Model:**  
  - TF-IDF + Logistic Regression (trained on custom-labeled dataset)

---

## 📦 Installation

```bash
git clone https://github.com/Sanket0307/Resume-Analyzer.git
cd Resume-Analyzer
pip install -r requirements.txt
streamlit run app.py
