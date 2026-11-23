## 📄 Resume Analyzer

A Python-based web application that analyzes how closely a resume matches a given job description using Natural Language Processing (NLP), TF-IDF vectorization, and Cosine Similarity.

## 📌 Overview

Resume Analyzer allows users to upload a resume in PDF format and paste a job description. The application extracts the text from the resume, preprocesses both texts, and calculates a similarity score to estimate how closely the resume aligns with the job requirements.

The application is built with Streamlit to provide a simple and interactive web interface.

## ✨ Features

- Upload a resume in PDF format
- Extract text from PDF resumes
- Clean and preprocess text
- Remove common English stopwords
- Convert resume and job description text into TF-IDF vectors
- Calculate similarity using Cosine Similarity
- Display an overall resume-job match percentage
- Visualize the match score
- Interactive Streamlit interface

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Scikit-learn**
- **NLTK**
- **PyPDF2**
- **NumPy**
- **Pandas**
- **Matplotlib**

## 🔍 How It Works

```text
Resume PDF
     ↓
PDF Text Extraction
     ↓
Text Cleaning
     ↓
Stopword Removal
     ↓
TF-IDF Vectorization
     ↓
Cosine Similarity
     ↓
Match Score
     ↓
Streamlit Visualization
