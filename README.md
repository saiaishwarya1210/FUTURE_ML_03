# 📌 Resume Screening & Candidate Ranking System (ML + NLP)

## 🚀 Overview
This project is an AI-powered Resume Screening System that automatically analyzes resumes, extracts relevant skills, and ranks candidates based on their suitability for a given job role using Machine Learning and Natural Language Processing (NLP).

It helps automate the hiring process by reducing manual effort and improving accuracy in candidate selection.

---

## 🎯 Problem Statement
Recruiters often receive hundreds of resumes for a single job role. Manually screening each resume is:

- Time-consuming  
- Prone to human bias  
- Inconsistent across candidates  

This project solves these issues using an automated ML-based ranking system.

---

## 💡 Solution
This system uses NLP techniques to:

- Extract skills and keywords from resumes  
- Compare resumes with job descriptions  
- Calculate similarity scores  
- Rank candidates based on relevance  

---

## 🧠 How It Works

1. Load resume dataset  
2. Clean and preprocess text data  
3. Extract skills and keywords  
4. Convert text into vectors using TF-IDF  
5. Compute similarity between resume and job role  
6. Rank candidates based on score  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLP (TF-IDF)  
- Jupyter Notebook  

---

## 📊 Output Example

| Candidate ID | Role | Score |
|--------------|------|-------|
| 1218 | CONSULTANT | 11.21 |
| 1339 | AUTOMOBILE | 9.08 |
| 1303 | DIGITAL MEDIA | 8.46 |
| 1040 | SALES | 8.10 |

---

## 🚀 Key Features

- Automated resume screening  
- Skill extraction using NLP  
- Candidate ranking system  
- Job-role matching  
- Reduces manual HR workload  

---

## 📁 Project Structure

resume-screening-system/
├── notebooks/
├── data/
├── src/
├── output/
├── requirements.txt
└── README.md

---

## 👨‍💻 Author
Built as part of Future Interns Machine Learning Task 3 (2026)

---

## ⭐ Future Improvements

- Streamlit web app for resume upload  
- Better skill extraction using spaCy  
- Dashboard visualization  
- Deployment as web app  
