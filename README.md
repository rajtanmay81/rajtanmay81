# Hi 👋, I'm Tanmay Raj

### AI Developer · Python · Machine Learning · RAG · GenAI

I build AI systems end to end: train and explain ML models, serve them through FastAPI, and wrap them in apps people can use. Java and Spring Boot are my backend foundation, Python is where I do my AI work.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

---

## 🚀 About me

- 🔭 **Building:** ML pipelines, RAG chatbots and LLM-powered apps with Python
- 🌱 **Exploring:** LLM applications, retrieval (FAISS, pgvector), explainable AI and shipping models to production
- 💬 **Ask me about:** Python, machine learning, FastAPI, RAG, SQL
- ☕ **Also comfortable with:** Java and Spring Boot
- 🎯 **Looking for:** AI/ML roles and internships where I can build and ship real models
- 📫 **Reach me:** [rajtanmay81@gmail.com](mailto:rajtanmay81@gmail.com)
- ⚡ **Fun fact:** I started with Java but fell in love with Python while exploring AI/ML

---

## 📌 Featured projects

### 🏥 [CareSight: Healthcare No-Show Prediction](https://github.com/rajtanmay81/healthcare-no-show-prediction)
An end-to-end hospital appointment system that predicts which appointments will be missed, explains each prediction, and includes a GenAI assistant for reminders and analytics.
- Compared Logistic Regression, Random Forest and XGBoost with a **temporal train/validation/test split** to avoid leakage; the selected model reaches **ROC-AUC 0.68 and 62% no-show recall** on the test set (synthetic data)
- **SHAP explanations** for every prediction, shown as readable factors
- GenAI assistant with a **grounding guard**: every number in an LLM answer is checked against SQL-computed facts, with a deterministic fallback
- JWT auth with role-based access, Alembic migrations, Docker Compose, React dashboard

`Python` `FastAPI` `scikit-learn` `XGBoost` `SHAP` `PostgreSQL` `React` `TypeScript` `Docker`

### 🎫 [Customer Support Ticket System with AI Triage](https://github.com/rajtanmay81/customer-support-ticket-system)
A full-stack ticketing platform where an AI assistant handles new tickets first and escalates to a human when the customer is frustrated.
- **Classifier** (TF-IDF + Logistic Regression) for ticket category and priority, with an **active-learning loop** that retrains on human corrections from the admin UI
- **RAG similar-ticket search** and canned-response suggestions using Gemini embeddings and **pgvector**
- Sentiment-based escalation, AI agent assignment, SLA tracking, live WebSocket updates, analytics dashboard

`Python` `FastAPI` `scikit-learn` `Gemini API` `Groq` `pgvector` `React`

### 🤖 [AI-FIRMFINDER: RAG Chatbot](https://github.com/rajtanmay81/AI-FIRMFINDER)
A company FAQ assistant that retrieves the most relevant passages from a knowledge base and answers from them.
- Overlapping document chunking, **sentence-transformers** embeddings (all-MiniLM-L6-v2) and a persistent **FAISS** index
- Local LLM answers through **Ollama**, grounded in the retrieved context
- FastAPI backend with email OTP verification

`Python` `FastAPI` `FAISS` `sentence-transformers` `Ollama` `SQLAlchemy`

### 🎙️ [AI Interview System](https://github.com/rajtanmay81/AI-Interview-System)
An AI interviewer that reads a resume, asks personalised questions and scores each answer.
- Resume parsing (PDF, DOCX, TXT) and **Gemini**-generated questions by skill and experience level
- Answers scored 0-10 with feedback, plus a final report with a hiring recommendation
- Browser-side proctoring: camera face detection, fullscreen enforcement and voice answers

`Python` `Gemini API` `JavaScript`

### 🎭 [Real-Time Face Emotion Detection](https://github.com/rajtanmay81/Face-Emotion-Detection)
A webcam app that detects faces and classifies seven emotions live.
- **MTCNN** face detection with a Keras CNN (64x64 grayscale input)
- Frame skipping and prediction smoothing for stable, low-latency output with confidence scores

`Python` `TensorFlow/Keras` `OpenCV` `MTCNN`

---

## 🛠️ Tech stack

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**GenAI and retrieval**

![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Backend, data and tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

---

## 📊 GitHub stats

<p>
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=rajtanmay81&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rajtanmay81&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 🤝 Connect with me

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rajtanmay81)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rajtanmay81@gmail.com)
<!-- Add your own links below, then delete this comment:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-ID)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/YOUR-LEETCODE-ID)
-->
