# AI Resume Screening & Job Matching Automation

## 📌 Overview

An AI-powered resume screening and job matching automation built using **n8n** and **Google Gemini**.

The workflow analyzes a candidate's resume against a given job description, calculates a match score, identifies matching and missing skills, stores the results in Google Sheets, and sends an email notification when the candidate meets the required score.

## 🔄 Workflow

Resume Upload → PDF Text Extraction → Google Gemini AI Analysis → Structured Output → Google Sheets → Match Score Check → Gmail Notification

## ✨ Features

- 📄 Upload resumes through an n8n form
- 🔤 Extract text from PDF resumes
- 🤖 Analyze resumes using Google Gemini
- 🎯 Compare candidate skills with job requirements
- 📊 Generate a match score out of 100
- ✅ Identify matching and missing skills
- 🎓 Evaluate education and project relevance
- 📋 Store screening results in Google Sheets
- 🔀 Apply conditional logic based on match score
- 📧 Send Gmail notifications for strong matches (80+)

## 🛠️ Technologies Used

- **n8n** – Workflow automation
- **Google Gemini** – AI-powered resume analysis
- **Google Sheets** – Store screening results
- **Gmail** – Recruiter notifications
- **PDF Extraction** – Resume text processing

## ⚙️ How It Works

1. Candidate resume and job description are submitted through an n8n form.
2. The uploaded PDF resume is converted into text.
3. Google Gemini analyzes the resume against the job description.
4. The AI generates structured screening information.
5. Results are stored automatically in Google Sheets.
6. The match score is checked using conditional logic.
7. If the score is **80 or higher**, a Gmail notification is sent.

## 📊 Output

The workflow generates:

- Candidate Name
- Match Score
- Key Skills
- Matching Skills
- Missing Skills
- Education Relevance
- Project Relevance
- Recommendation

### Recommendation Categories

- **Strong Match**
- **Moderate Match**
- **Weak Match**

## 🚀 Future Enhancements

- Support multiple resume formats
- Add candidate ranking
- Process multiple resumes automatically
- Add recruiter dashboard
- Integrate with job portals
- Add interview scheduling automation

## 👨‍💻 Author

**Prasanna Papisetti**

---

⭐ If you find this project useful, feel free to star the repository.
