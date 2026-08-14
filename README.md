<div align="center">

# Vankadoth Praveen 👋

**AI/ML Engineer in the Making · LLM Systems · Agentic AI · Research-Driven Builder**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/v-praveen/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:v.praveen0700@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/9raveen)
[![Visitors](https://visitcount.itsvg.in/api?id=9raveen&label=Profile%20Views&color=6&icon=0&pretty=true)](https://visitcount.itsvg.in)

</div>

---

## 🧠 About Me

I'm a **pre-final year B.Tech Computer Science (AI/ML)** student at **IIIT Nagpur**, graduating May 2027. My work sits at the intersection of **ML engineering**, **LLM-based systems**, and **real-world deployment** — I don't just train models, I ship them.

- 🧩 Shipped a **Multi-Agent RAG Research Assistant** — a production-grade research pipeline built on LangGraph, Groq, Qdrant Cloud & FastAPI, deployed at zero infra cost
- 🏢 Designed **Think9 Decision Intelligence OS** — an agentic decision-memory system that lets a multi-brand consumer company surface cross-brand precedent before repeating past mistakes
- 🏆 Built **FacetBench** — a production-ready conversation scoring benchmark system (LangGraph + Qwen2.5-7B + ChromaDB + Docker), live in production
- 🧪 Deep interest in **LLM orchestration**, **evaluation frameworks (RAGAS)**, and **multi-agent pipeline design**
- 🌱 Currently sharpening: **LlamaIndex**, **CrewAI**, vector database internals, LLM evaluation methodology
- 💡 Long-term goal: ML Engineer focused on **LLM-based and agentic AI systems**

---

## 🚀 Featured Projects

### 🤖 Multi-Agent RAG Research Assistant
> LangGraph · Groq (Llama-3.3-70B) · Qdrant Cloud · FastAPI · React/Vite · Neon Postgres

A full multi-agent research pipeline where independent agents handle retrieval, synthesis, and self-critique — built end-to-end and shipped on a strict zero-infrastructure-cost budget.

- **ResearchAgent → SynthesisAgent → CritiqueAgent** loop with automatic retry on weak answers
- PDF ingestion, multi-turn chat with query rewriting, and real-time streaming via SSE
- Live agent trace panel exposing each step of the reasoning pipeline
- Multi-user JWT authentication with persistent chat history on Neon Postgres
- Long-document summarization via Qdrant scroll API with a map-reduce strategy
- Evaluated with **RAGAS**: 0.9542 faithfulness, 1.0000 context recall
- Deployed: FastAPI on Hugging Face Spaces (Docker), React frontend on Vercel

---

### 🏢 Think9 Decision Intelligence OS
> LangGraph · Multi-Agent Retrieval · Structured Decision Memory · Human-in-the-Loop Governance

An agentic framework designed to answer one question before any major cross-brand decision: *"has this already been learned somewhere else in the organization?"* Built for a consumer-brand portfolio operating across dozens of brands and suppliers, where institutional memory is siloed and identical mistakes get repeated at scale.

- **Router → Retrieval → Cross-Brand Intelligence → Decision Synthesis** agent pipeline, with deterministic governance and human-approval gates instead of a black-box confidence score
- **"Ask Think9"** natural-language Q&A plus a **Decision Explorer** for browsable precedent discovery (e.g. supplier → brands that used it → past decisions → known issues)
- Confidence is evidence-backed — every answer cites the corroborating historical record rather than an arbitrary percentage
- Explicitly designed to say "no relevant precedent found" or flag conflicting precedents for human review, instead of forcing an oversimplified answer
- Reframes retrieval from generic semantic similarity to **precedent relevance** — grounded in a structured decision-log dataset spanning multiple brands and suppliers

---

### 📊 FacetBench — Conversation Scoring Benchmark
> LangGraph · Qwen2.5-7B · Ollama · ChromaDB · FastAPI · Streamlit · Docker

End-to-end LLM evaluation system that benchmarks multi-turn conversations across quality facets, live in production.

- 8-node LangGraph pipeline scoring 399 facets across conversations
- ChromaDB + all-MiniLM-L6-v2 for semantic context retrieval
- 57x reduction in LLM inference calls through pipeline optimization
- Full Docker containerization, 26 pytest tests, CI-ready structure
- Deployed: FastAPI on Render, Streamlit UI on Streamlit Cloud → **[facetbench.onrender.com](https://facetbench.onrender.com)**

---

### ⚡ Hybrid Physics-ML Digital Twin for Microgrids
> pandapower · XGBoost · Random Forest · Newton-Raphson Load Flow · Streamlit

Physics-informed ML system for microgrid blackout prediction and energy load forecasting.

- AC Newton-Raphson power flow solver (IEEE 33-bus topology) integrated with an ML prediction layer
- XGBoost ROC-AUC 0.9711, Random Forest R² 0.8646
- Battery Energy Storage System (BESS) / SOC dynamics modeling
- Targeting IEEE publication; deployed as an interactive Streamlit dashboard

---

### 🎯 Multi-Object Tracking Pipeline (FA Cup Footage)
> YOLOv8m · DeepSORT · HSV K-Means · HuggingFace Spaces

Real-time player detection and team classification pipeline on soccer broadcast video.

- Kalman filter-based trajectory prediction via DeepSORT
- Unsupervised team separation using custom HSV color clustering
- Live demo deployed on HuggingFace Spaces

---

### 🔐 Network Intrusion Detection System (CICIDS2017)
> XGBoost · LightGBM · Random Forest · SMOTE · Scikit-learn

Production-grade IDS on 2.8M records across 80+ features.

- Three-stage feature selection pipeline (ExtraTreesClassifier → PowerTransformer → SMOTE)
- 9-model benchmark reaching ~99% F1 score
- Co-authored research paper, IIIT Nagpur

---

## 💻 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

**ML / DL**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![XGBoost](https://img.shields.io/badge/XGBoost-%23376EB2.svg?style=for-the-badge&logo=xgboost&logoColor=white)

**LLM / Agentic AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-%231a1a2e.svg?style=for-the-badge&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-FF4040?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-black?style=for-the-badge&logoColor=white)

**Data & Visualization**

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Backend & Deployment**

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=9raveen&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Streak Stats](https://nirzak-streak-stats.vercel.app/?user=9raveen&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=9raveen&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

</div>

---

## 📌 Currently

```
🔨 Building  →  Agentic AI systems with structured memory & multi-agent orchestration
📚 Learning  →  LLM Evaluation | LlamaIndex | CrewAI | Vector DB internals
🎯 Target    →  ML / AI Engineering Internships (2025–26)
📍 Based in  →  Hyderabad, India
```

---

<div align="center">

*"Strong fundamentals + consistency > talent 💡"*

</div>
