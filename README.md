

# 🤖 Intervux AI

**An intelligent AI-powered interview preparation platform powered by Groq AI (Llama 3.3).**

Analyze resumes, practice realistic AI interviews, receive personalized feedback, and track your career readiness — all in one platform.

[![Live App](https://img.shields.io/badge/Live%20App-Online-brightgreen?style=for-the-badge)](https://intervux-ai-10.onrender.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/YAKSHITH684/Intervux-AI)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Groq](https://img.shields.io/badge/AI-Groq%20Llama%203.3-orange?style=for-the-badge)](https://groq.com/)


---

## 📑 Table of Contents

- [Live Deployment](#-live-deployment)
- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Solution](#-solution)
- [Features](#-features)
- [How Intervux AI Works](#-how-intervux-ai-works)
- [AI Workflow](#-ai-workflow)
- [AI Integration](#-ai-integration)
- [Technology Stack](#️-technology-stack)
- [Project Structure](#️-project-structure)
- [Local Installation](#️-local-installation)
- [API Endpoints](#-api-endpoints)
- [Deployment](#️-deployment)
- [Project Statistics](#-project-statistics)
- [Why Intervux AI?](#-why-intervux-ai)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🌐 Live Deployment

🚀 **Live Application:** [intervux-ai-10.onrender.com](https://intervux-ai-10.onrender.com/)

📂 **GitHub Repository:** [github.com/YAKSHITH684/Intervux-AI](https://github.com/YAKSHITH684/Intervux-AI)

---

## 📌 Project Overview

Intervux AI is an AI-powered interview preparation platform designed to help students, fresh graduates, and job seekers improve their interview skills.

The platform combines **Artificial Intelligence, Resume Analysis, and Mock Interview Simulation** to create a realistic interview preparation experience.

Users can upload resumes, receive ATS analysis, practice AI-generated interviews, get personalized feedback, and track their improvement over time.

---

## 🎯 Problem Statement

Many students and job seekers struggle to perform well in interviews because they lack:

- Realistic interview practice
- Personalized feedback
- Resume optimization guidance
- Confidence before interviews
- Access to professional coaching

Traditional preparation methods provide limited practice and do not identify individual weaknesses. Intervux AI solves this problem by providing an AI-powered personal interview coach available anytime.

---

## 💡 Solution

Intervux AI provides an intelligent platform where candidates can:

- ✅ Analyze their resume using AI
- ✅ Practice real-time AI mock interviews
- ✅ Receive personalized feedback
- ✅ Identify skill gaps
- ✅ Track interview readiness
- ✅ Improve confidence before real interviews

---

## ✨ Features

| Feature | Description |
|---|---|
| 📄 Resume Intelligence | Upload PDF/DOCX/TXT resume and receive AI ATS score, skills, strengths, and suggestions |
| 🤖 AI Interview Coach | Realistic AI interviews with Technical, HR, System Design, and DSA modes |
| 🎯 Smart Practice Mode | Generate topic-based questions and receive personalized AI feedback |
| 📊 Career Dashboard | Track interview readiness, skills, progress, and improvement areas |
| 💬 AI Career Assistant | AI chatbot for interview preparation and career guidance |
| 🔐 User Authentication | Register, login, and password recovery system |

---

## 🚀 How Intervux AI Works

```
1. User uploads resume
        ↓
2. Resume parser extracts information
        ↓
3. Groq AI analyzes resume
        ↓
4. ATS score, skills, and suggestions generated
        ↓
5. AI conducts mock interview
        ↓
6. Answers are evaluated with feedback
        ↓
7. Progress and readiness are tracked
```

---

## 🧠 AI Workflow

**Resume Intelligence**

```
Resume File
     ↓
PDF/DOCX Parser
     ↓
Text Extraction
     ↓
Groq Llama 3.3 AI
     ↓
ATS Score · Skill Detection · Strength Analysis · Suggestions
```

**AI Interview Engine**

```
Candidate Answer
     ↓
AI Interview System
     ↓
Response Understanding
     ↓
Performance Evaluation
     ↓
Personalized Feedback
```

---

## 🤖 AI Integration

**AI Provider:** Groq API
**AI Model:** Llama 3.3-70B-Versatile

AI powers three core areas:

**📄 Resume Analysis**
- Resume content extraction
- ATS compatibility scoring
- Skill identification
- Strength analysis
- Improvement recommendations

**🎤 AI Interview Simulation**

Supports Technical, HR, System Design, and DSA interviews, with:
- Dynamic questions
- Follow-up questions
- Answer evaluation
- Feedback generation

**💬 AI Assistant**
- Interview preparation tips
- Career guidance
- Resume advice
- Learning recommendations

---

## 🛠️ Technology Stack

**Frontend**
- HTML5, CSS3, JavaScript
- Responsive Web Design
- Glassmorphism UI
- Render Static Hosting

**Backend**
- Python 3, FastAPI
- SQLAlchemy, SQLite Database
- Groq API, Llama 3.3 AI Model
- pdfplumber, python-docx
- REST API Architecture

**Deployment**
- Render Cloud Platform

---

## 🗂️ Project Structure

```
Intervux-AI/
│
├── Frontend/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── resume.html
│   ├── ai_analysis.html
│   ├── interview.html
│   ├── practice.html
│   ├── progress.html
│   ├── resources.html
│   ├── style.css
│   └── script.js
│
└── Backend/
    ├── app.py
    ├── routes.py
    ├── requirements.txt
    └── database/
        ├── database.py
        └── models.py
```

---

## ⚙️ Local Installation

### Clone the repository

```bash
git clone https://github.com/YAKSHITH684/Intervux-AI.git
cd Intervux-AI
```

### Backend setup

```bash
cd Backend
python -m venv venv
```

Activate the environment (Windows):

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Environment variables

Add your Groq API key.

Windows:

```cmd
set GROQ_API_KEY=your_groq_api_key_here
```

Linux/Mac:

```bash
export GROQ_API_KEY=your_groq_api_key_here
```

### Run backend

```bash
uvicorn app:app --reload
```

Backend runs at:

```
http://127.0.0.1:8000
```

### Run frontend

Open another terminal:

```bash
cd Frontend
python -m http.server 5500
```

Open in browser:

```
http://localhost:5500/login.html
```

---

## 📡 API Endpoints

| Endpoint | Purpose |
|---|---|
| `/register` | User registration |
| `/login` | User authentication |
| `/forgot-password` | Password reset |
| `/analyze-resume` | AI resume analysis |
| `/chat` | AI interview conversation |
| `/assistant` | AI career assistant |
| `/practice/questions` | Generate questions |
| `/practice/feedback` | Evaluate answers |
| `/ai-analysis` | Resume insights |

---

## ☁️ Deployment

**Platform:** Render Static Site
**Live URL:** [intervux-ai-10.onrender.com](https://intervux-ai-10.onrender.com/)

---

## 📊 Project Statistics

| Metric | Count |
|---|---|
| Total Files | 20+ |
| Frontend Pages | 10 |
| REST APIs | 9 |
| AI Features | 5 |
| Interview Modes | 4 |
| Database | SQLite |
| AI Model | Groq Llama 3.3-70B |
| Resume Formats | PDF, DOCX, TXT |
| Deployment | Render |

---

## 🌟 Why Intervux AI?

Traditional interview preparation has real limitations:

- ❌ Limited practice opportunities
- ❌ No personalized feedback
- ❌ Expensive coaching
- ❌ No resume improvement guidance

Intervux AI addresses each of these:

- ✅ AI-powered interview simulation
- ✅ Real-time feedback
- ✅ Resume intelligence
- ✅ Personalized preparation
- ✅ Career readiness tracking

---

## 🔮 Future Enhancements

- 🎙️ Voice-based AI interviews
- 🎥 Video interview analysis
- 📈 Interview history tracking
- 📄 AI resume builder
- 🏢 Company-specific interview preparation
- 🏆 Candidate leaderboard
- 📱 Mobile application
- 📧 Email reminders

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve Intervux AI:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is currently unlicensed. If you plan to reuse or build on this code, please reach out to the author first, or add a license (e.g. MIT) if you intend to open it up for public use.

---

## 👨‍💻 Author

**Yakshith Anandapu**

GitHub: [@YAKSHITH684](https://github.com/YAKSHITH684)

Built with ❤️ using FastAPI, JavaScript, SQLite, Groq AI, Llama 3.3, and Render Cloud.

⭐ If you find this project useful, consider giving it a star on GitHub!</p>

### Your Personal AI Interview Coach

**Prepare Smarter • Practice Better • Get Hired**

</p>
