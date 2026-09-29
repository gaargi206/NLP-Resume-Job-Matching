# NLP-Based Job Description Analysis and Resume Matching System

## 📌 Project Overview

This project develops an NLP-based system for matching resumes with relevant job descriptions.

The system combines traditional Natural Language Processing techniques with semantic embeddings and skill matching to rank job postings according to their relevance to a given resume.

The project uses TF-IDF, cosine similarity, Sentence Transformers, and normalized skill extraction to generate an explainable hybrid matching score.

---

## 🎯 Objectives

- Analyze job descriptions using Natural Language Processing.
- Preprocess and normalize job-related text.
- Match resumes with relevant job postings.
- Calculate TF-IDF-based similarity.
- Calculate semantic similarity using Sentence Transformers.
- Extract and compare relevant skills.
- Identify matched and missing skills.
- Rank job postings using a hybrid matching score.

---

## 📊 Dataset

The project uses the **Job Description Dataset** available on Kaggle.

Dataset source:

https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset

The dataset contains approximately **78,705 job postings** and **23 columns**.

Important fields used in this project include:

- Job Title
- Role
- Qualifications
- Job Description
- Skills
- Responsibilities

The dataset contains job postings and does not contain verified resume–job matching labels. Therefore, the project does not claim conventional classification accuracy.

---

## 🧠 Methodology

The system follows a multi-stage NLP pipeline:

```text
Resume
   ↓
Text Preprocessing
   ↓
TF-IDF Vectorization
   ↓
Top Candidate Job Retrieval
   ↓
Sentence Transformer Embeddings
   ↓
Semantic Similarity
   ↓
Skill Extraction & Matching
   ↓
Hybrid Matching Score
   ↓
Ranked Job Recommendations
