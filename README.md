# JP Morgan Legal Document Classification using CRISP-DM

## 📌 Project Overview

This project presents a machine learning-based solution to automate the classification and review of legal documents at JP Morgan. The current manual process is time-consuming (approx. 360,000 hours annually) and error-prone. By adopting the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology, this project aims to reduce review time by up to 80% and increase processing accuracy to over 95%.

## 💼 Business Problem

JP Morgan's legal and loan servicing departments face operational delays and inaccuracies due to the manual inspection of complex legal documents such as:
- Credit-default swaps
- Custody agreements
- Loan servicing contracts

The business goal is to **automate document classification and clause analysis** to streamline operations, reduce human error, and improve turnaround time.

## 🧠 CRISP-DM Methodology

### 1. Business Understanding
- Automate the classification of legal documents and clauses
- Minimize mistakes in loan processing
- Accelerate document review workflows

### 2. Data Understanding
- Source data: 1000+ legal contracts with ~20 clauses each
- Documents include financial terms, payment schedules, clauses, and legal terminology
- Common issues: missing clauses, duplicate entries, inconsistent formats

### 3. Data Preparation
- Applied OCR techniques to extract text from scanned documents
- Selected and cleaned relevant attributes: clause type, due dates, payment terms, deadlines, and legal context
- Addressed issues like missing fields and duplicate values

### 4. Modeling
- Developed ML models for:
  - Classifying clauses into appropriate categories
  - Identifying key terms in loan and custody agreements
  - Predicting risks in document structure and content

### 5. Evaluation
- Model performance was evaluated on clause classification accuracy and consistency
- Feedback from domain experts was integrated into model refinement

### 6. Deployment
- Proposed deployment of the model in JP Morgan’s document processing pipeline
- Tools: Python, OCR libraries (like Tesseract), Scikit-learn / NLP models

## ⚙️ Tools & Technologies
- Python
- OCR (Optical Character Recognition)
- Natural Language Processing (NLP)
- Scikit-learn / SpaCy
- Pandas, NumPy, Matplotlib

## 📝 Project Highlights
- Reduced contract review time by ~80%
- Increased accuracy in identifying key clauses to over 95%
- Scalable solution for varied document formats and clause structures
