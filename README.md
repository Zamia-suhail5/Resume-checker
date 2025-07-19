# Resume-checker# 🚀 Resume Analyzer Based on Job Description

This project is an AI-powered Resume Analyzer that helps job seekers optimize their resumes for a specific job description (JD). It uses OCR, NLP, and a predefined skills database to score resumes and suggest the best-fit roles based on content matching.

## 🔍 Features

- 📄 Upload a resume in PDF format
- 📝 Paste a job description (JD)
- 🎯 Get an ATS (Applicant Tracking System) match score
- 💡 Receive intelligent suggestions and best-fit roles
- 📊 Visual representation with a pie chart
- 🧠 Role-based skills detection for:
  - AI/ML Intern
  - Data Analyst
  - Web Developer
  - Backend Developer
  - Cloud Engineer
  - DevOps Engineer
  - Cybersecurity Analyst
  - Data Scientist
  - Business Analyst
  - Full Stack Developer

## 🧠 How It Works

1. **Text Extraction**: Converts uploaded PDF resumes to text using OCR (Tesseract).
2. **JD Keyword Analysis**: Tokenizes the job description and extracts meaningful keywords.
3. **Skill Matching**: Compares resume content against predefined skill sets for popular roles.
4. **Scoring**: Calculates ATS match score based on skills detected.
5. **Role Suggestion**: Recommends the best-fit roles and suggests improvements.
6. **Visualization**: Displays results using a pie chart and markdown messages via a Gradio interface.

## 📦 Dependencies

Make sure to install the following Python libraries and system packages:

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
apt-get install -y poppler-utils
