# 🚀 AI Career Copilot

An AI-powered Resume Analysis Platform built using Flask, Gemini AI, SQLAlchemy, and TiDB Cloud.

## 📌 Overview

AI Career Copilot helps students and job seekers analyze their resumes and identify:

- ✅ Existing Skills
- ❌ Missing Skills
- 🛣 Personalized Learning Roadmap
- 🎯 Interview Preparation Questions

The system uses Google's Gemini AI to provide career-focused recommendations based on the user's target role.

---

## ✨ Features

### 🔐 Authentication
- User Signup
- User Login
- Session Management

### 📄 Resume Analysis
- Paste Resume Text
- Upload PDF Resume
- Upload DOCX Resume

### 🤖 AI Analysis
- Skills Extraction
- Missing Skills Detection
- Personalized Career Roadmap
- Interview Questions Generation

### 📚 History Tracking
- Store Previous Analyses
- View Analysis History

---

## 🛠 Tech Stack

### Backend
- Python
- Flask
- SQLAlchemy

### Database
- TiDB Cloud
- MySQL Compatible Database

### AI
- Google Gemini AI

### Frontend
- HTML5
- CSS3
- Jinja2 Templates

---

## 📂 Project Structure

```text
AI RESUME
│
├── app.py
├── ai.py
├── db.py
├── models.py
├── create_tables.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── static/
│   └── style.css
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   └── history.html
│
└── venv/
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Career-Copilot.git
cd AI-Career-Copilot
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file:

```env
GEMINI_API_KEY=YOUR_API_KEY
DATABASE_URL=YOUR_DATABASE_URL
SECRET_KEY=YOUR_SECRET_KEY
```

---

## ▶️ Run Application

```bash
python app.py
```

Application will start at:

```text
http://127.0.0.1:5000
```

---

## 🎯 Future Enhancements

- Resume Score System
- ATS Compatibility Checker
- Resume PDF Report Download
- Job Recommendation Engine
- AI Career Mentor Chatbot
- LinkedIn Profile Analyzer

---

## 👨‍💻 Developer

**Rahul Gunjal**

Software Developer | AI Enthusiast | Python Developer

---

