# FUTURE_ML_03

# Overview

This project is an NLP-based Resume Screening and Candidate Ranking System developed using Python and Machine Learning techniques. The system automatically analyzes resumes, extracts important skills, compares resumes with job descriptions, calculates similarity scores, ranks candidates, and identifies missing skills.

The project simulates the basic workflow of an Applicant Tracking System (ATS) used in modern recruitment platforms.

---

# Features

* Resume text preprocessing and cleaning
* Stopword removal and tokenization
* Skill extraction using NLP
* TF-IDF vectorization
* Cosine similarity-based resume matching
* Candidate ranking system
* Skill gap analysis
* Interactive resume screening using user input
* Data visualizations for skill analysis and candidate ranking

---

# Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn

---

# Dataset

The project uses a resume dataset containing resumes from multiple professional domains such as HR, Engineering, Business Development, Banking, Information Technology, Healthcare, and Sales.

Due to GitHub file size limitations, the dataset ZIP file is not included in this repository.

A similar dataset can be downloaded from Kaggle:
https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset

After downloading the dataset:

* upload the ZIP file into the notebook environment
* run the notebook cells sequentially

---

# Project Workflow

1. Load and extract the dataset ZIP file
2. Read resume dataset using Pandas
3. Clean and preprocess resume text
4. Remove stopwords and tokenize text
5. Extract candidate skills
6. Create job descriptions
7. Convert text into TF-IDF vectors
8. Calculate cosine similarity between resumes and job descriptions
9. Rank candidates based on similarity scores
10. Identify missing skills
11. Visualize extracted skills and candidate rankings
12. Run interactive resume screening using user input

---

# How to Run the Project

## Step 1 — Open the Notebook

Open the notebook file:

```text
FUTURE_ML_03.ipynb
```

---

## Step 2 — Upload Dataset ZIP File

Make sure the dataset ZIP file:

```text
archive (4).zip
```

is uploaded into the notebook environment.

---

## Step 3 — Run All Cells Sequentially

Run the notebook cells from top to bottom in order.

The notebook will:

* extract the ZIP dataset
* preprocess resumes
* perform NLP analysis
* rank candidates
* generate visualizations

---

## Step 4 — Use Interactive Resume Screening

At the end of the notebook, an interactive screening system allows users to:

* enter a custom job description
* enter a custom resume
* receive:

  * extracted skills
  * similarity score
  * missing skills

Example:

```text
Enter Job Description:
Looking for a Data Scientist skilled in Python, SQL, NLP, and Machine Learning.

Enter Resume Text:
Experienced Data Scientist skilled in Python, SQL, TensorFlow, and NLP.
```

---

# Visualizations

The notebook includes:

* Top extracted skills visualization
* Candidate similarity score visualization

These graphs help analyze workforce skills and candidate rankings.

---

# Conclusion

This project developed an NLP-based Resume Screening and Candidate Ranking System using Python and Machine Learning techniques. The system preprocesses resume text, extracts important skills, compares resumes with job descriptions using TF-IDF and Cosine Similarity, and ranks candidates based on relevance. It also identifies missing skills to help recruiters evaluate applicants more efficiently. The project demonstrates a practical implementation of an Applicant Tracking System (ATS) used in modern recruitment workflows.

---

# Future Improvements

* Add PDF resume parsing
* Use advanced NLP models like BERT
* Implement Named Entity Recognition (NER)
* Build a web-based ATS dashboard
* Add resume upload functionality
* Improve semantic skill matching

---

# Internship Task

Future Interns — Machine Learning Task 3

Resume / Candidate Screening System
