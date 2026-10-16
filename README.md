
# 🤖 Intervux AI

### Your Personal AI Interview Coach

**Prepare Smarter • Practice Better • Get Hired**

Analyze your resume, practice realistic AI mock interviews, get instant personalized feedback, and track your career readiness, all in one platform.

<br>

[![Live App](https://img.shields.io/badge/Live%20App-Online-brightgreen?style=for-the-badge)](https://intervux-ai-10.onrender.com/01_login.html)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/YAKSHITH684/Intervux-AI)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Groq](https://img.shields.io/badge/AI-Groq%20Llama%203.3-orange?style=for-the-badge)](https://groq.com/)

<br>

**[🚀 Try the Live App](https://intervux-ai-10.onrender.com/01_login.html)** · **[📂 View Source](https://github.com/YAKSHITH684/Intervux-AI)** · **[🐞 Report a Bug](https://github.com/YAKSHITH684/Intervux-AI/issues)**

</div>

---

## 📑 Table of Contents

- [Live Demo](#-live-demo)
- [Overview](#-overview)
- [The Problem](#-the-problem)
- [The Solution](#-the-solution)
- [Features](#-features)
- [How It Works](#-how-it-works)
- [AI Integration](#-ai-integration)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#️-project-structure)
- [Getting Started](#️-getting-started)
- [API Reference](#-api-reference)
- [Deployment](#️-deployment)
- [At a Glance](#-at-a-glance)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🌐 Live Demo

| | Link |
|---|---|
| 🚀 **Live App** | [intervux-ai-10.onrender.com](https://intervux-ai-10.onrender.com/) |
| 🔑 **Login Page** | [intervux-ai-10.onrender.com/01_login.html](https://intervux-ai-10.onrender.com/01_login.html) |
| 📂 **GitHub Repo** | [github.com/YAKSHITH684/Intervux-AI](https://github.com/YAKSHITH684/Intervux-AI) |

---

## 📌 Overview

**Intervux AI** helps students, fresh graduates, and job seekers get interview-ready. It combines **resume analysis**, **AI mock interviews**, and **progress tracking** into one realistic preparation experience, available any time, with no coach required.

Upload your resume, get an ATS score and improvement tips, practice interviews in four different modes, and see exactly where to improve.

---

## 🎯 The Problem

Most candidates struggle in interviews because they lack:

- Realistic interview practice
- Personalized, honest feedback
- Resume optimization guidance
- Confidence going in
- Access to affordable professional coaching

Traditional preparation offers limited practice and rarely pinpoints an individual's weak spots.

## 💡 The Solution

Intervux AI acts as an always-available personal interview coach:

| You want to... | Intervux AI gives you |
|---|---|
| Know if your resume is strong | AI-powered ATS score, skills, strengths, and suggestions |
| Practice for real | Dynamic mock interviews with follow-up questions |
| Know what to fix | Personalized feedback on every answer |
| Stay on track | A dashboard tracking readiness and progress |
| Get unstuck | An AI career assistant for tips and guidance |

---

## ✨ Features

| Feature | Description |
|---|---|
| 📄 **Resume Intelligence** | Upload a PDF, DOCX, or TXT resume and get an ATS score, detected skills, strengths, and improvement suggestions |
| 🎤 **AI Interview Coach** | Realistic interviews in **Technical**, **HR**, **System Design**, and **DSA** modes |
| 🎯 **Smart Practice Mode** | Generate topic-based questions and get personalized feedback on your answers |
| 📊 **Career Dashboard** | Track interview readiness, skills, progress, and areas to improve |
| 💬 **AI Career Assistant** | Chat for interview prep, resume advice, and career guidance |
| 🔐 **User Authentication** | Register, log in, and recover your password |

---

## 🚀 How It Works

```mermaid
flowchart LR
    A[📄 Upload Resume] --> B[🔍 Parse & Extract Text]
    B --> C[🧠 Groq AI Analysis]
    C --> D[📊 ATS Score, Skills, Suggestions]
    D --> E[🎤 AI Mock Interview]
    E --> F[✅ Answer Evaluation & Feedback]
    F --> G[📈 Progress & Readiness Tracking]
```

**Resume pipeline:** Resume file → PDF/DOCX parser → text extraction → Groq Llama 3.3 → ATS score, skills, strengths, suggestions

**Interview pipeline:** Candidate answer → AI interview engine → response understanding → performance evaluation → personalized feedback

---

## 🧠 AI Integration

| | |
|---|---|
| **Provider** | [Groq API](https://groq.com/) |
| **Model** | Llama 3.3-70B-Versatile |

AI powers three core areas:

**📄 Resume Analysis**
- Content extraction
- ATS compatibility scoring
- Skill identification and strength analysis
- Improvement recommendations

**🎤 Interview Simulation**
- Technical, HR, System Design, and DSA modes
- Dynamic questions and follow-ups
- Answer evaluation and feedback generation

**💬 Career Assistant**
- Interview preparation tips
- Resume advice
- Career guidance and learning recommendations

---

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | HTML5, CSS3, JavaScript, responsive design, glassmorphism UI |
| **Backend** | Python 3, FastAPI, REST API architecture |
| **Database** | SQLAlchemy ORM, SQLite |
| **AI** | Groq API, Llama 3.3-70B-Versatile |
| **Parsing** | pdfplumber, python-docx |
| **Hosting** | Render |

---

## 🗂️ Project Structure

```
Intervux-AI/
│
├── Frontend/
│   ├── 01_login.html
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

## ⚙️ Getting Started

### Prerequisites

- Python 3.x
- A free [Groq API key](https://console.groq.com/)

### 1. Clone the repository

```bash
git clone https://github.com/YAKSHITH684/Intervux-AI.git
cd Intervux-AI
```

### 2. Set up the backend

```bash
cd Backend
python -m venv venv
```

Activate the virtual environment:

```bash
# Windows
venv\Scripts\activate

# Linux / macOS
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### 3. Add your Groq API key

```bash
# Windows (cmd)
set GROQ_API_KEY=your_groq_api_key_here

# Linux / macOS
export GROQ_API_KEY=your_groq_api_key_here
```

### 4. Run the backend

```bash
uvicorn app:app --reload
```

The API runs at `http://127.0.0.1:8000`

### 5. Run the frontend

In a new terminal:

```bash
cd Frontend
python -m http.server 5500
```

Open **http://localhost:5500/01_login.html** in your browser. 🎉

---

## 📡 API Reference

| Endpoint | Purpose |
|---|---|
| `/register` | User registration |
| `/login` | User authentication |
| `/forgot-password` | Password reset |
| `/analyze-resume` | AI resume analysis |
| `/ai-analysis` | Resume insights |
| `/chat` | AI interview conversation |
| `/assistant` | AI career assistant |
| `/practice/questions` | Generate practice questions |
| `/practice/feedback` | Evaluate practice answers |

> With the backend running locally, FastAPI's interactive docs are available at `http://127.0.0.1:8000/docs`.

---

## ☁️ Deployment

| | |
|---|---|
| **Platform** | Render |
| **Live URL** | [intervux-ai-10.onrender.com](https://intervux-ai-10.onrender.com/) |
| **Login Page** | [intervux-ai-10.onrender.com/01_login.html](https://intervux-ai-10.onrender.com/01_login.html) |

---

## 📊 At a Glance

| Metric | Value |
|---|---|
| Frontend pages | 10 |
| REST APIs | 9 |
| AI features | 5 |
| Interview modes | 4 (Technical, HR, System Design, DSA) |
| Resume formats | PDF, DOCX, TXT |
| Database | SQLite |
| AI model | Groq Llama 3.3-70B |

---

## 🔮 Roadmap

- [ ] 🎙️ Voice-based AI interviews
- [ ] 🎥 Video interview analysis
- [ ] 📈 Interview history tracking
- [ ] 📄 AI resume builder
- [ ] 🏢 Company-specific interview prep
- [ ] 🏆 Candidate leaderboard
- [ ] 📱 Mobile application
- [ ] 📧 Email reminders

Have an idea? [Open an issue](https://github.com/YAKSHITH684/Intervux-AI/issues), suggestions are welcome.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature`
5. Open a Pull Request

For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is currently unlicensed. If you plan to reuse or build on this code, please contact the author first, or add a license (e.g. MIT) if you intend to open it up for public use.

---

## 👨‍💻 Author

**Yakshith Anandapu**
GitHub: [@YAKSHITH684](https://github.com/YAKSHITH684)

<div align="center">

Built with ❤️ using FastAPI, JavaScript, SQLite, Groq AI, Llama 3.3, and Render.

⭐ If you find this project useful, consider giving it a star!

</div>


