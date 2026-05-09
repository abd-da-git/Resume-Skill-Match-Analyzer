# Resume Skill Match Analyzer

## Overview
The Resume Skill Match Analyzer is a Python-based project that compares a candidate’s resume with a job description. It extracts relevant skills, calculates a match score using NLP techniques, and provides a final recommendation based on compatibility.

---

##  Features
- PDF resume text extraction
- Text cleaning and preprocessing
- Skill extraction using keyword matching
- Job description comparison using TF-IDF
- Resume-job match percentage
- Skill gap analysis
- Simple recommendation system

---

##  Technologies Used
- Python
- PyPDF2 (PDF reading)
- Scikit-learn (TF-IDF & cosine similarity)
- NLTK (basic text processing)

---

## How It Works
1. Resume is loaded from a PDF file  
2. Text is extracted and cleaned  
3. Job description is entered manually  
4. Both texts are converted into numerical vectors using TF-IDF  
5. Cosine similarity is used to calculate match score  
6. Skills are compared with predefined skill list  
7. Final report is generated  

---

##  Output Example
- Match Score: 72%
- Skills Found: Python, SQL, Pandas
- Missing Skills: Flask, Django
- Recommendation: Moderate match, improve missing skills

---
