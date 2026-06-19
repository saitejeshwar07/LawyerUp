# ⚖️ LawyerUp

### AI-Powered Legal Assistance & Lawyer Discovery Platform

Understand legal problems. Analyze legal documents. Connect with the right lawyer.

LawyerUp is an AI-powered legal assistance platform designed to make legal support accessible, understandable, and affordable for everyone.

![React](https://img.shields.io/badge/Frontend-React-blue)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)
![Gemini](https://img.shields.io/badge/AI-Gemini-green)

---

## 🌐 Live Demo

🔗 https://lawyerup-fb623.web.app/

---

## ✨ What Makes LawyerUp Different?

| Traditional Legal Support     | LawyerUp                         |
| ----------------------------- | -------------------------------- |
| Expensive legal consultations | ⚡ Instant AI legal assistance    |
| Difficult legal terminology   | 📖 Simplified legal explanations |
| Manual document review        | 🤖 AI-powered document analysis  |
| Hard to find suitable lawyers | 👨‍⚖️ Smart lawyer discovery     |
| Limited accessibility         | 🌍 AI-assisted legal guidance    |

---

# 🏗️ System Architecture

```text
┌─────────────────────────────────────────┐
│         User Portal (React + Vite)      │
│               Port : 5173               │
└───────────────────┬─────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────┐
│          Firebase Backend               │
│                                         │
│ • Authentication                        │
│ • Firestore Database                    │
│ • Storage                               │
└───────────────────┬─────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────┐
│              AI Services                │
│                                         │
│ • Gemini API                            │
│ • LangChain                             │
│ • Pinecone Vector Database              │
│ • Groq LLM                              │
└───────────────────┬─────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────┐
│          Google Maps Platform           │
│                                         │
│ • Maps API                              │
│ • Places API                            │
│ • Geocoding API                         │
└─────────────────────────────────────────┘
```

---

# 🎯 User Journey

```text
 SIGNUP → LOGIN → ASK AI → ANALYZE DOCUMENT → FIND LAWYER

    │         │          │              │               │
    ▼         ▼          ▼              ▼               ▼

 Firebase  Dashboard   LawBot    AI Analyzer   Lawyer Search
```

---

# 🚀 Core Features

## 🤖 AI Legal Assistant (LawBot)

* Conversational AI chatbot for legal guidance
* Legal rights and procedure explanations
* Context-aware responses using RAG
* Powered by Gemini, LangChain, Pinecone, and Groq

---

## 📄 AI Document Analyzer

* Upload legal documents
* AI-generated summaries
* Clause explanations
* Key point extraction
* Simplified legal interpretations
* Multilingual support

---

## 👨‍⚖️ Smart Lawyer Discovery

* Search lawyers by:

  * Practice Area
  * Location
  * Experience
  * Gender
* Google Maps integration
* Location-based lawyer discovery

---

## 📚 Legal Resource Repository

* Legal templates
* Legal resources
* Common legal documents
* Public legal information

---

## 👤 User Dashboard

* Manage profile
* Track uploaded documents
* Store AI interactions
* Manage lawyer searches

---

## 🔒 Secure Authentication

* Firebase Authentication
* Protected user accounts
* Secure cloud-based storage

---

# 🗓️ Development Roadmap

* **Phase 1 – Problem Research & Idea Validation**
* **Phase 2 – Project Planning & System Design**
* **Phase 3 – Frontend Development**
* **Phase 4 – Firebase Integration**
* **Phase 5 – AI Legal Assistant (LawBot)**
* **Phase 6 – Legal Knowledge Base**
* **Phase 7 – AI Document Analyzer**
* **Phase 8 – Smart Lawyer Discovery**
* **Phase 9 – Testing & Deployment**

---

# 📂 Project Structure

```text
LawyerUp/
│
├── .github/
│   └── workflows/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── ML/
│   ├── AI_DOC_ANALYSER/
│   ├── CHATBOT/
│   └── proactive_agent/
│
├── public/
│   ├── assets/
│   ├── logo.png
│   ├── lawyer.svg
│   └── index.html
│
├── firebase.json
├── storage.rules
├── README.md
└── .gitignore
---

# 🚀 Quick Start

## Prerequisites

* Node.js 18+
* Python 3.10+
* Firebase Project
* Gemini API Key
* Pinecone API Key
* Groq API Key
* Google Maps API Key

---

## 1. Clone Repository

```bash
git clone https://github.com/saitejeshwar07/LawyerUp.git
cd LawyerUp
```

---

## 2. Start AI Document Analyzer

```bash
cd ML/AI_DOC_ANALYSER
python app.py
```

---

## 3. Start LawBot

```bash
cd ML/CHATBOT/law
python app.py
```

---

## 4. Start Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 5. Open Application

```text
http://localhost:5173
```

---

# 🛠️ Technology Stack

| Layer           | Technology         |
| --------------- | ------------------ |
| Frontend        | React.js + Vite    |
| Styling         | Tailwind CSS       |
| Authentication  | Firebase Auth      |
| Database        | Firebase Firestore |
| Storage         | Firebase Storage   |
| AI Assistant    | Gemini API         |
| RAG Framework   | LangChain          |
| Vector Database | Pinecone           |
| LLM             | Groq               |
| Maps & Location | Google Maps API    |
| Deployment      | Firebase Hosting   |

---

# 🗓️ Future Roadmap

* ✅ AI Legal Assistant
* ✅ AI Document Analyzer
* ✅ Smart Lawyer Discovery
* ✅ Firebase Authentication
* 🔄 Lawyer Appointment Booking
* 🔄 Real-Time Lawyer Chat
* 🔄 AI Legal Document Generation
* 🔄 Court Procedure Guidance
* 🔄 Case Tracking Dashboard
* 🔄 Regional Language Support
* 🔄 Voice-Based Legal Assistant

---

# 🤝 Contributing

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to GitHub
5. Open a Pull Request

---

---
👨‍💻 Built by Pawar Sai Tejeshwar

B.Tech, Chemical Engineering
Indian Institute of Technology Gandhinagar (IITGN)
