
<h1 align="center">Yves Alikalfic</h1>
<p align="center">
  I like to build products — full-stack • AI-adjacent • practical UX
  <br/>
  <a href="https://github.com/yves-a/resume/blob/master/Yves_Alikalfic_Resume.pdf"><img alt="Resume" src="https://img.shields.io/badge/Resume-PDF-informational?logo=adobeacrobatreader&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/yves-alikalfic/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin"></a>
  <a href="mailto:alikalfic.yves@queensu.ca"><img alt="Email" src="https://img.shields.io/badge/Email-alikalfic.yves%40queensu.ca-red?logo=gmail&logoColor=white"></a>
</p>

---

## 👋 About
CS-minded builder focused on shipping small, useful products. Recently:
- A **simple ATS** that compares resumes vs JDs using LLM embeddings (Java ↔ Python services + web UI).
- Lightweight web apps (real-time chat in Flask/Socket.IO, medical-record CRUD).
- Visual/learning projects (sorting visualizer, Swift iOS mini-apps).

I value clean READMEs, reproducible setups, and small demos people can actually run.

---

## 🧰 Tech stack
**Languages:** TypeScript/JavaScript, Python, Java, Swift  
**Frontend:** React, CRA/Vite, HTML/CSS  
**Backend:** FastAPI, Flask-SocketIO, Node, Java (Maven)  
**Infra/Dev:** Docker & Compose, Nginx, GitHub Actions  
**Data/AI:** Embeddings (Ollama/LLM backends), service orchestration

---

## 🔥 Highlights
### 1) Simple ATS — Java + Python + React, Dockerized
**Repo:** [`simple-ats`](https://github.com/yves-a/simple-ats)  
**What it does:** Compares resumes and job descriptions via embeddings with a Java service calling a Python FastAPI service; dev/prod via Docker Compose.  
**Run:** `./start-dev.sh` (local dev) or `./start.sh prod` (compose).  
**Notes:** Connects to Ollama locally or as a container; separate Java/Python services for clarity.  
**Stack:** Java (Maven), Python (FastAPI), TypeScript, Docker, Nginx.

---

### 2) Sift - Gift Recommender — web + mobile (K-means, RN swipe UI)
**Repo:** [`sift`](https://github.com/yves-a/sift)  
**What it does:** Personalized gift suggestions via K-means on user preferences/behavior; shipped as web + React Native app. Drove **60 sales** from **1.3k+ users** and lifted engagement **1.75×** (session duration, DAU) after adding a Tinder-style swipe UI.  
**Good for:** Recommender systems, RN gesture UX, analytics/experimentation.

---

### 3) Annie Chat Bot — medical simulation (Cohere, TTS, BLE vitals)
**Repo:** [`annie-chat-bot`](https://github.com/yves-a/annie-chat-bot)  
**What it does:** Simulates a patient for training: answers clinician questions using Cohere, responds via text-to-speech (pyttsx3), and streams real-time vitals from lab sensors over Bluetooth. Improved medical students’ response time **40%** in lab trials.  
**Good for:** LLM-in-the-loop sims, TTS pipelines, Bluetooth/BLE device integration, real-time vitals UX.

---

### 4) Giggle Gear — Adobe CC web add-on (React/TS)
**Repo:** [`giggle-gear`](https://github.com/yves-a/giggle-gear)  
**What it does:** Starter add-on scaffold using React/TypeScript and Adobe tooling.  
**Good for:** Plugin/add-on architecture, bundling.

---

### 5) Medical Record Application — full-stack (TS)
**Repo:** [`medical-record-application`](https://github.com/yves-a/medical-record-application)  
**What it does:** Minimal patient record CRUD with split frontend/backend.  
**Stack:** TypeScript + simple API.

---


## 📎 Quick links
- **Resume:** [PDF](https://github.com/yves-a/resume/blob/master/Yves_Alikalfic_Resume.pdf)  
- **LinkedIn:** https://www.linkedin.com/in/yves-alikalfic/  
- **GitHub profile:** https://github.com/yves-a  

---

## 🤝 Open to
Junior SWE roles (full-stack/backend), internships, and small collaborations.  
For a quick repo tour or feedback, email **alikalfic.yves@queensu.ca**.
