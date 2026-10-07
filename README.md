<h1 align="center">Hi, I'm Aditya Pal 👋</h1>

<p align="center">
  <b>Agentic AI & LLM Engineer in the making</b> · Backend developer · Competitive programmer
</p>

<p align="center">
  <a href="https://linkedin.com/in/aditya2964"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:adityapal70078@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://adityapal2964.github.io/my_portfolio/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

---

## 🧠 About Me

- 🎓 B.Tech CSE student at **NIET, Greater Noida** (2023 – 2027)
- 🤖 I build **agentic AI systems**: multi-agent architectures with supervisor/critic orchestration, LLM tool-calling, and hybrid RAG
- ⚙️ Backed by strong backend skills in **Java, Spring Boot, Kafka, Redis, and Docker**
- 🏆 **1800+ rating (Knight) on LeetCode**, 500+ problems solved across LeetCode and Codeforces
- 🥈 2nd place at CodeMaverick Programming Contest · Team Lead at **Smart India Hackathon 2025**

---

## 🚀 Featured Projects

### 🤖 [DocuAgent](https://github.com/adityapal2964/Multi-Agent-Document-Intelligence-System): Multi-Agent Document Intelligence
A LangGraph system where an LLM-driven **supervisor** routes work between **retriever, summarizer, and critic** agents.
- Critic agent checks answer groundedness and loops back to the retriever with a refined query on failure
- RAG pipeline (PDF/TXT/MD → chunking → embeddings → FAISS) with page-level citations
- Real LLM tool-calling: AST calculator, read-only SQL tool, Tavily web search
- FastAPI backend + Streamlit UI, offline fallback mode, **35 passing pytest tests**

`LangGraph` `LangChain` `FastAPI` `FAISS` `SQLite` `Streamlit` `Tavily` `pytest`

### 🎥 [YouTube RAG Chatbot](https://github.com/aditya2964/yt-rag): Conversational Video Q&A
Ask multi-turn questions about any YouTube video, with answers grounded strictly in the transcript.
- **Hybrid retriever**: BM25 + FAISS dense search (50/50 weighting, top-6 chunks)
- LLM-based **query rewriting** and multi-turn conversational memory
- Powered by **Groq-hosted Llama 3.3 70B**

`LangChain` `FAISS` `BM25` `HuggingFace` `Groq`

### 🚗 [Co-Ride](https://github.com/adityapal2964/CoRide): Geospatial Ride-Sharing Platform
A map-centric, event-driven full-stack platform.
- PostGIS + GiST indexing for sub-second geospatial queries
- Kafka event pipelines for ride status and driver matching
- Redis location cache cut matching latency by **45%** (180ms → 100ms)
- Fully containerized with Docker, cutting setup time by **60%**

`Java` `Spring Boot` `PostgreSQL` `PostGIS` `Kafka` `Redis` `Docker` `React` `Leaflet.js`

### 🛰️ [SIH 2025: ShuddhData & GNSS](https://github.com/adityapal2964/)
Led a 4-member team at Smart India Hackathon 2025.
- LSTM-based GNSS signal forecasting model, **12% lower MAE** across 50,000+ data points
- C++ secure data sanitization utility (Gutmann and DoD wiping algorithms)

`Python` `TensorFlow` `C++` `Linux`

---

## 🛠️ Tech Stack

**Agentic AI & LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Data**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Tools & Frontend**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=adityapal2964&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityapal2964&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 🏆 Highlights

| | |
|---|---|
| 🧩 Problems solved | 500+ on LeetCode & Codeforces (DP, Graphs, Greedy, Recursion) |
| ⭐ LeetCode | 1800+ rating (Knight) |
| 🥈 Contest | 2nd place, CodeMaverick Programming Contest |
| 🇮🇳 Hackathon | Team Lead, Smart India Hackathon 2025 |
| 📜 Certifications | Infosys Springboard (DSA), Deloitte Australia Tech Job Simulation (Forage) |

---

## 🌱 Currently

- 🔧 Containerizing DocuAgent for cloud deployment with Bedrock / Azure OpenAI integration
- 📚 Going deeper into multi-agent orchestration and LLM tool use

## 🤝 Open To

Internships, collaborations on **agentic AI / LLM apps**, and backend engineering roles.

<p align="center">
  <i>Building agents that plan, reason, and act. 🚀</i>
</p>
