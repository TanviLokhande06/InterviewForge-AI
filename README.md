# 🚀 InterviewForge AI

An AI-powered interview preparation platform that analyzes resumes, self descriptions and job descriptions to generate personalized interview strategies, technical questions, behavioral questions, skill-gap analysis, and learning roadmaps.

---

## 📌 Overview

InterviewForge AI helps candidates prepare effectively for technical interviews by leveraging Generative AI. Users can upload their resume, provide a self-description, and paste a target job description. The platform evaluates compatibility, identifies missing skills, and creates a customized preparation plan.

---

## ✨ Features

### 📄 Resume Analysis

* Upload PDF resumes
* Extract and analyze resume content
* Identify strengths and relevant experience

### 🎯 Job Description Matching

* Analyze target job requirements
* Compare candidate profile with role expectations
* Generate a match score

### 🤖 AI-Powered Interview Report

* Personalized interview strategy
* Skill gap analysis
* Technical interview questions
* Behavioral interview questions
* Preparation roadmap

### 📊 Skill Gap Detection

Identify missing or weak skills required for the target role.

### 📥 AI Resume Generation

Generate an optimized resume based on:

* Existing resume content
* Self-description
* Target job requirements

### 📚 Learning Roadmap

Receive actionable recommendations for:

* Technologies to learn
* Projects to build
* Concepts to revise
* Interview preparation priorities

---

## 🖥️ Tech Stack

### Frontend

* React.js
* React Router
* Context API
* SCSS
* Axios
* Vite

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* Multer
* PDF Parser

### AI Integration

* Google Gemini API

### Authentication

* JWT Authentication
* Cookie-Based Sessions

---

## 📂 Project Structure

```bash
project-root/
│
├── Frontend/
│   ├── src/
│   │   ├── features/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── context/
│   │   └── styles/
│
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/TanviLokhande06/InterviewForge-AI.git
cd InterviewForge-AI
```

---

### Backend Setup

```bash
cd Backend
npm install
```

Create `.env`:

```env
PORT=3000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
```

Start backend:

```bash
npm run dev
```

---

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

## 🚀 How It Works

### Step 1

Upload your resume (PDF).

### Step 2

Provide a professional self-description.

### Step 3

Paste the target job description.

### Step 4

Generate your personalized interview report.

### Step 5

Review:

* Match Score
* Skill Gaps
* Technical Questions
* Behavioral Questions
* Learning Plan

---

## 📸 Screenshots

### Interview Strategy Generator

Generate AI-powered interview preparation plans based on your resume and target role.

### Interview Report Dashboard

View skill gaps, interview questions, and preparation recommendations.

---

## 🔮 Future Improvements

* AI Mock Interviews
* Voice-Based Interview Practice
* ATS Resume Scoring
* Company-Specific Interview Questions
* Interview Performance Analytics
* Multi-Language Support
* Resume Optimization Suggestions

---

## 👨‍💻 Author

Built with ❤️ using React, Node.js, Express, MongoDB, and Google Gemini AI.
