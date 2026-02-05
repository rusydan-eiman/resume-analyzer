<div align="center">
  <div>
    <img alt="React" src="https://img.shields.io/badge/React-4c84f3?style=for-the-badge&logo=react&logoColor=white">
    <img alt="Tailwind" src="https://img.shields.io/badge/-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
    <img alt="Puter.js" src="https://img.shields.io/badge/Puter.js-181758?style=for-the-badge&logoColor=white">
  </div>

  <h3 align="center">AI Resume Analyzer</h3>

  <p align="center">
    A personal engineering project exploring zero-backend architecture and AI semantic analysis.
  </p>
</div>

---

## 🚀 Why I Built This

I built this **AI Resume Analyzer** for my own use and learning. I wanted to understand exactly how Applicant Tracking Systems (ATS) evaluate my own resumes and decided to build a private, transparent version that I control. 

This project served as a way for me to experiment with **Puter.js** and see how far I could push a "Zero-Backend" architecture while maintaining full functionality.

## 📜 Note on Project History

Although the initial commits for this repository are recent, this project was developed as part of my earlier learning journey before I fully adopted **Git and GitHub** as my primary version control workflow. I am committing it now to document my technical growth and to maintain a professional record of the architecture and logic I implemented.

## 🛠️ My Implementation

### 1. My Serverless Approach (Puter.js)
I chose to bypass traditional Node/Express backends entirely. By using **Puter.js**, I implemented:
* **My Private Auth**: Secure login for myself and my sessions directly in the frontend.
* **Personal Cloud Storage**: I store my own PDF/Docx resumes in my private Puter cloud.
* **Direct Database Access**: Handling my analysis history without managing a separate server.

### 2. My AI Logic & Prompting
I built a logic flow that goes beyond keyword matching. I wanted the AI to understand the *context* of my experience.
* **Personalized Scoring**: I designed a scoring logic to give me a quantitative look at my resume's strength.
* **My Gap Analysis**: The system tells me exactly what I'm missing for specific roles I'm interested in.

### 3. My Frontend Stack
* **React & TypeScript**: My choice for maintaining a clean, type-safe codebase.
* **React Router v7**: How I manage navigation between my dashboard and my analysis views.
* **Zustand**: My preferred lightweight state management to keep my app fast.
* **Tailwind CSS**: I designed this UI for my own workflow—clean, fast, and professional.

## 🔋 Core Capabilities I Implemented

* **My Resume Parsing**: I built the extraction logic to handle my own resume formats.
* **Tailored Matching**: I can paste any job listing I'm targeting to get immediate feedback.
* **My Dashboard**: A place where I track my own progress and versioning.
* **Full Data Privacy**: I ensured my data stays in my own cloud instance—no middleman.

---

<p align="center">
  Built for my own growth with focus on <b>Performance</b>, <b>Privacy</b>, and <b>AI Logic</b>.
</p>
