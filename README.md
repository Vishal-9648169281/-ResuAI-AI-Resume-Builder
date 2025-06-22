# -ResuAI-AI-Resume-Builder
ResuAI is an AI-powered resume builder that uses NLP to analyze job descriptions and generate optimized resumes with keyword matching. Built with Python, Flask, and scikit-learn.
# ResuAI – AI-Powered Resume Analyzer and Builder

**ResuAI** is a full-stack web application designed to help job seekers tailor their resumes to match specific job descriptions (JDs) using Natural Language Processing (NLP). It analyzes the resume content, extracts keywords from the job description, and shows how well the resume aligns with the job role.

---

## 🎯 Project Goals

- Upload resume in PDF format
- Paste the job description in a form
- Extract key terms and skills from the JD using NLP
- Parse the resume and match it against the extracted keywords
- Display a compatibility score and matched keywords
- Help users understand where their resume can improve

---

## 🧩 Key Features

- **Resume Upload:** Upload PDF resumes via web interface
- **Job Description Input:** Paste JD text in a textbox
- **NLP Keyword Extraction:** Extract relevant keywords using AI
- **Keyword Matching:** Compare resume content with JD keywords
- **Score Display:** Show percentage match and list of matched keywords
- **Simple UI:** Built with clean HTML and CSS (can use Bootstrap)
- **Backend in Flask:** Python-powered API to process and analyze text
- **Resume Parsing:** Uses PyMuPDF (`fitz`) to read PDF content

---

## ⚙️ Tech Stack

| Layer     | Technology                        |
|-----------|-----------------------------------|
| Frontend  | HTML, CSS, JavaScript (optional)  |
| Backend   | Python, Flask                     |
| AI/NLP    | spaCy, scikit-learn, NLTK         |
| Parser    | PyMuPDF (fitz)                    |
| Hosting   | Localhost / Heroku / Render       |

---
