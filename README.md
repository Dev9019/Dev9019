## Hi, I'm Debasish Paul 👋

### AI Engineer | Python Developer | Generative AI | AI Agents

I build practical AI applications that transform real-world problems into intelligent, usable solutions.

My work focuses on Machine Learning, Generative AI, LLM applications, AI Agents, and Python backend systems using modern AI frameworks and developer tools.

I work on artificial intelligence, machine learning, natural language processing, AI agents, and backend API development. I enjoy transforming ideas into practical solutions using modern AI frameworks and developer tools.

## About Me

- 🔭 Currently building AI agents, NLP applications, and machine learning APIs.
- 🌱 Currently learning advanced AI engineering, LLM applications, and multi-agent systems.
- 💡 Interested in artificial intelligence, NLP, semantic search, automation, and developer tools.
- 🧠 Experienced with FastAPI, LangChain, CrewAI, Hugging Face, and Ollama.
- 🛠️ Focused on developing reliable backend systems and AI-powered applications.
- 📍 Based in Dhaka, Bangladesh.
- 🤝 Open to collaboration on AI, machine learning, and software development projects.

## Technical Skills

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

### Programming Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### AI and Machine Learning

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge)

### Backend and Development

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Databases and Tools

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### Databases and Tools

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Featured Projects

## Featured Projects

### [CareerPilot AI](https://github.com/Dev9019/CareerPilot-AI)

# 🚀 CareerPilot AI

### AI-Powered Resume Analyzer & Career Assistant

AI-powered resume analyser and career assistant built with FastAPI, Google Gemini, and pdfplumber.

The application analyses resumes across multiple professional criteria and generates a resume score, professional summary, strengths, missing skills, and actionable improvement suggestions.

---
GitHub Topics

python · fastapi · generative-ai · gemini · llm · resume-analyzer · ai · career-assistant · pdf-processing · rest-api


## 🎯 Project Overview

CareerPilot AI was built to help job seekers understand how effectively their resume communicates their skills, experience, and career potential.

Users upload a PDF resume through the web interface. The FastAPI backend extracts the resume text, sends it to the Gemini-powered analysis engine, and returns structured JSON containing personalised career insights.

### Key Capabilities

* 📄 PDF resume upload
* 🤖 AI-powered resume analysis
* ⭐ Resume scoring from 0–100
* 📝 Professional summary generation
* 💪 Strength identification
* 🔎 Missing skill identification
* 💡 Actionable resume improvement suggestions
* 📊 ATS compatibility evaluation
* 🎯 Job-readiness assessment
* ⚡ FastAPI REST API
* 🧠 Structured JSON AI responses

---

## 🧠 Resume Evaluation Framework

CareerPilot AI evaluates resumes across **10 key areas**:

1. ATS Compatibility
2. Professional Summary
3. Technical Skills
4. Work Experience
5. Projects
6. Education
7. Certifications
8. Measurable Achievements
9. Formatting & Readability
10. Overall Job Readiness

### Scoring System

| Score    | Rating                        |
| -------- | ----------------------------- |
| 90–100   | Outstanding                   |
| 80–89    | Excellent                     |
| 70–79    | Good                          |
| 60–69    | Average                       |
| Below 60 | Needs Significant Improvement |

The AI is instructed to provide balanced, constructive, and practical feedback based on the candidate's career level and target role.

---

## 🔄 How It Works

```text
User
  │
  ▼
Upload PDF Resume
  │
  ▼
Frontend
  │
  ▼
FastAPI Backend
  │
  ▼
PDF Text Extraction
(pdfplumber)
  │
  ▼
CareerPilot AI Analysis Engine
  │
  ▼
Google Gemini API
(Gemini 3 Flash Preview)
  │
  ▼
Structured JSON Response
  │
  ├── Resume Score
  ├── Professional Summary
  ├── Strengths
  ├── Missing Skills
  └── Improvement Suggestions
  │
  ▼
Frontend Results
```

---

## 🏗️ System Architecture

### Frontend

Built with:

* HTML
* CSS
* JavaScript

Responsible for:

* Resume upload
* User interaction
* Displaying AI-generated results

### Backend

Built with:

* Python
* FastAPI
* Uvicorn

Responsible for:

* REST API endpoints
* PDF upload handling
* File validation
* Resume processing
* Communication with the AI engine
* Returning structured analysis results

### Document Processing

**pdfplumber** is used to extract text from uploaded PDF resumes.

### AI Engine

CareerPilot AI uses the **Google Gemini API** to analyze extracted resume content.

The AI engine is configured to return structured JSON containing:

```text
resume_score
professional_summary
strengths
missing_skills
suggestions
```

---

## 🛠️ Tech Stack

| Category             | Technologies           |
| -------------------- | ---------------------- |
| Programming Language | Python                 |
| Backend Framework    | FastAPI                |
| AI / LLM             | Google Gemini API      |
| Model                | Gemini 3 Flash Preview |
| PDF Processing       | pdfplumber             |
| API Server           | Uvicorn                |
| Configuration        | python-dotenv          |
| Frontend             | HTML, CSS, JavaScript  |
| API Style            | REST                   |
| Version Control      | Git, GitHub            |

---

## 📂 Project Structure

```text
CareerPilot-AI/
│
├── backend/
│   ├── main.py
│   ├── ai_engine.py
│   ├── utils.py
│   ├── .env
│   └── uploads/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── .gitignore
├── requirements.txt
├── vercel.json
└── README.md
```

> **Note:** The `.env` file should remain local and must never be committed to GitHub.

---

## ⚙️ Getting Started

### Prerequisites

Make sure you have:

* Python 3.12+
* Git
* A Google Gemini API key

### 1. Clone the Repository

```bash
git clone https://github.com/Dev9019/CareerPilot-AI.git

cd CareerPilot-AI
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file inside the `backend` directory:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Never commit your API key to GitHub.

### 5. Start the Backend

```bash
cd backend

python -m uvicorn main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```

### 6. Open the Frontend

Open:

```text
frontend/index.html
```

in your browser and upload a PDF resume.

---

## 🔌 API Endpoint

### Analyze Resume

**Endpoint**

```text
POST /analyze
```

Accepts:

* PDF resume file

Returns structured JSON containing:

```json
{
  "resume_score": 85,
  "professional_summary": "...",
  "strengths": [],
  "missing_skills": [],
  "suggestions": []
}
```

### Health Check

**Endpoint**

```text
GET /
```

Returns:

```json
{
  "message": "CareerPilot AI API is running!"
}
```

---

## 📸 Application Demo

Add screenshots of the application here to demonstrate:

* Resume upload interface
* AI analysis results
* Resume score
* Strengths and missing skills
* Improvement suggestions

> Screenshots are recommended because they allow recruiters to understand the application immediately without reading the entire README.

---

## 🌐 Deployment

CareerPilot AI has been prepared for deployment using **Vercel**.

**Live Demo:**
https://career-pilot-ai-gray-phi.vercel.app

> If the deployed version is unavailable, the application can be run locally using the setup instructions above.

---

## 💡 Engineering Highlights

This project demonstrates practical experience with:

* AI-powered document analysis
* LLM API integration
* Prompt engineering
* Structured JSON generation
* REST API development
* FastAPI backend architecture
* PDF text extraction
* File validation and temporary file management
* Environment-variable configuration
* Frontend/backend integration
* Git-based version control

---

## 🔮 Future Improvements

Potential future enhancements include:

* 🎯 Job-description matching
* 📊 Advanced ATS analysis
* 🧩 Skill-gap analysis
* 💼 Personalized career recommendations
* 🔎 Job recommendation functionality
* 📄 Resume optimization for specific roles
* 🧠 Retrieval-Augmented Generation (RAG)
* 🔐 User authentication
* ☁️ Production-ready cloud deployment
* 📈 Resume improvement tracking

---

## 👨‍💻 Author

### Debasish Paul

**AI Engineer | Python Developer | Generative AI | AI Agents**

* 💻 GitHub: https://github.com/Dev9019
* 🔗 LinkedIn: https://www.linkedin.com/in/debasish-paul-4877991b9/

---

⭐ If you find CareerPilot AI interesting, feel free to explore the repository.


## ⚙️ Getting Started

### Prerequisites

Make sure you have:

* Python 3.12+
* Google Gemini API
* Gemini 3 Flash Preview
* Git

You also need the **Llama 3.2** model available locally through Ollama.

### 1. Clone the repository

```bash
git clone https://github.com/Dev9019/CareerPilot-AI.git

cd CareerPilot-AI
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start Ollama

Make sure Ollama is running and the required Llama model is available.

### 5. Start the FastAPI backend

```bash
cd backend

python -m uvicorn main:app --reload
```

The API will be available locally at:

```text
http://127.0.0.1:8000
```

### 6. Open the frontend

Open:

```text
frontend/index.html
```

in your browser.

---

## 📸 Application Demo

Upload a PDF resume and receive an AI-generated analysis containing:

**Resume Score → Professional Summary → Strengths → Missing Skills → Improvement Suggestions**

> Add project screenshots or a short demo GIF here to give recruiters an immediate visual understanding of the application.

---

## 🌐 Live Demo

**Live Demo:**
https://career-pilot-ai-gray-phi.vercel.app

> The live deployment depends on the AI/backend configuration. For the most reliable experience, follow the local setup instructions above.

---

## 💡 Key Engineering Concepts Demonstrated

This project demonstrates practical experience with:

* AI application architecture
* LLM integration
* Local LLM inference
* Prompt-based AI analysis
* PDF document processing
* REST API development
* FastAPI backend development
* Frontend/backend integration
* Git-based version control
* Full-stack AI application development

---

## 🔮 Future Improvements

Planned improvements include:

* 📊 More advanced resume scoring
* 🎯 Job-description matching
* 🧩 Skill-gap analysis
* 📄 ATS optimization
* 💼 Personalised career recommendations
* 🔎 Job recommendation capabilities
* 🧠 Retrieval-Augmented Generation (RAG)
* ☁️ Production-ready cloud LLM integration
* 🔐 Improved authentication and data security

---

## 👨‍💻 Author

**Debasish Paul**

AI Engineer | Python Developer | Generative AI | AI Agents

* GitHub: https://github.com/Dev9019
* LinkedIn: https://www.linkedin.com/in/debasish-paul-4877991b9/

---

⭐ If you find this project interesting, feel free to explore the repository.


**Tech Stack:** Python, FastAPI, Gemini 3 Flash Preview, PyMuPDF, JavaScript, HTML, CSS, and Uvicorn.

**Live Demo:** [career-pilot-ai-gray-phi.vercel.app](https://career-pilot-ai-gray-phi.vercel.app)

### [Bangladesh Multi-Tool AI Agent](https://github.com/Dev9019/Bangladesh-MultiTool-AI-Agent)

A multi-tool AI agent that works with Bangladesh-related datasets and information using LangChain, Ollama, SQLite, and web search.

**Tech Stack:** Python, LangChain, Ollama, SQLite, and web search.

### [Amar Passport AI Agent](https://github.com/Dev9019/Amar-Passport-AI-Agent)

A multi-agent Bangladesh passport assistance system developed with CrewAI. The system uses collaborative AI agents to help users access passport-related information and guidance.

**Tech Stack:** Python, CrewAI, Ollama, and large language models.

### [Leo Multi-Agent AI Tutor](https://github.com/Dev9019/Leo-Multi-Agent-AI-Tutor-)

A multi-agent AI tutor that plans lessons, teaches students, creates quizzes, and evaluates learning progress through collaborative AI agents.

**Tech Stack:** Python, CrewAI, Ollama, and artificial intelligence.

### [Heart Diseases API](https://github.com/Dev9019/heart-diseases-api)

A machine learning API that provides heart-disease predictions through a backend service built with Python and FastAPI.

**Tech Stack:** Python, machine learning, FastAPI, and REST API development.

### [LinkedIn Post Generator Agent](https://github.com/Dev9019/linkdin-post-generator-agent-)

An AI-powered content-generation agent designed to create professional LinkedIn posts with the help of language models and automated workflows.

A multi-agent AI tutor that plans lessons, teaches students, creates quizzes, and evaluates learning progress through collaborative AI agents.

**Tech Stack:** Python, CrewAI, Ollama, and artificial intelligence.


## Development Focus

- AI agents and multi-agent systems
- Large language model applications
- Natural language processing
- Machine learning model deployment
- Semantic search and vector databases
- FastAPI backend development
- AI automation workflows
- Scalable and reliable APIs

- ## GitHub Statistics

![Debasish's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Dev9019&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Dev9019&layout=compact&theme=tokyonight&hide_border=true)

[![GitHub Streak](https://streak-stats.demolab.com?user=Dev9019&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

## GitHub Activity
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Dev9019&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Dev9019&layout=compact&theme=tokyonight&hide_border=true

## Connect With Me

- GitHub: [@Dev9019](https://github.com/Dev9019)
- LinkedIn: [Debasish Paul](https://www.linkedin.com/in/debasish-paul-4877991b9/)

## My Goal

My goal is to become a highly skilled AI Engineer and contribute to meaningful projects that use artificial intelligence to solve real-world problems.
