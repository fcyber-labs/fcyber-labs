
# Hey, I'm Fcyber 👋

I build AI systems that actually work in production — not just in notebooks.

My focus is the full stack between a research paper and a deployed model: fine-tuning, agent orchestration, MLOps pipelines, and the infrastructure that keeps everything running reliably. I care about what happens after the demo, which means proper logging, testing, CI/CD, and experiment tracking from day one.

Most of my work is open source. If something I built saves you a week of debugging, that's the point.

---

## What I specialise in

**LLM Fine-Tuning** — domain-specific models trained on high-quality, custom-built datasets. Not generic instruction tuning. Purpose-built models that reason differently because they were trained differently. My current flagship is [FinReasoner](https://huggingface.co/fcyber/FinReasoner-qwen2.5-14b-instruct) — a Qwen 2.5 14B model fine-tuned on 12,500 gold-standard SEC filing analyses across 580 companies and 5 years of data. The dataset took about 30,000 LLM calls and a multi-agent generator-auditor pipeline to build. The model does causal financial reasoning, not summarization.

**AI Agents** — single agents, multi-agent systems, agentic RAG, voice agents, browser agents. Built with LangGraph, CrewAI, and AutoGen depending on what the task needs. Every project has a live demo on Hugging Face Spaces so you can try it before cloning anything.

**MLOps & LLMOps** — experiment tracking with MLflow, pipeline orchestration with Apache Airflow, containerization with Docker and Docker Compose, CI/CD with GitHub Actions and GitLab CI. Every project is dockerized and pushed to Docker Hub. Every ML experiment is tracked. Nothing runs only on my machine.

---

## Technical stack

### AI & ML

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Transformers](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-7C3AED?style=flat-square) ![CrewAI](https://img.shields.io/badge/CrewAI-FF6B6B?style=flat-square) ![AutoGen](https://img.shields.io/badge/AutoGen-0078D4?style=flat-square) ![Unsloth](https://img.shields.io/badge/Unsloth-%E2%9A%A1-orange?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/Anthropic-CC5A4A?style=flat-square) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square) ![Loguru](https://img.shields.io/badge/Loguru-Logging-4B8BBE?style=flat-square)

### Fine-tuning

![LoRA](https://img.shields.io/badge/LoRA%20%2F%20rsLoRA-blueviolet?style=flat-square) ![QLoRA](https://img.shields.io/badge/QLoRA-7C3AED?style=flat-square) ![DoRA](https://img.shields.io/badge/DoRA-9333EA?style=flat-square) ![PEFT](https://img.shields.io/badge/PEFT-FF9D00?style=flat-square) ![TRL](https://img.shields.io/badge/TRL%20%2F%20DPO-1C3C3C?style=flat-square) ![BitsAndBytes](https://img.shields.io/badge/BitsAndBytes-4--bit-00A86B?style=flat-square&logo=cpu&logoColor=white)

### MLOps & Infrastructure

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Loguru](https://img.shields.io/badge/Loguru-Logging-4B8BBE?style=flat-square)

### Backend & Data

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square) ![Weaviate](https://img.shields.io/badge/Weaviate-FF5A5F?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

## Projects

### 🤖 AI Agents — [ai-engineering-hub](https://github.com/fcyber-labs/ai-engineering-hub)

Five production-grade agent projects, all dockerized, all with live demos on Hugging Face Spaces.

| Project                       | What it does                                                       | Demo                                                                 |
| ----------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------- |
| **Agentic RAG Assistant**     | Self-correcting Q&A with hallucination detection and hybrid search | [▶ Try it](https://huggingface.co/spaces/fcyber/agentic_rag)         |
| **Voice AI Assistant**        | Speak → AI response → downloadable audio. Multi-language.          | [▶ Live app](https://fcyber-labs-voice-ai-assistant.streamlit.app/)  |
| **AI Podcast Generator**      | News URLs → produced podcast episode with MP3                      | [▶ Try it](https://huggingface.co/spaces/fcyber/ai-podcast)          |
| **YouTubeScriptMaster**       | Any YouTube video → structured script, insights, markdown export   | [▶ Try it](https://huggingface.co/spaces/fcyber/YouTubeScriptMaster) |
| **AI Presentation Generator** | Plain text → full PowerPoint deck with AI-generated images         | [▶ Try it](https://huggingface.co/spaces/fcyber/YouTubeScriptMaster) |

Stack across these projects: LangGraph · CrewAI · AutoGen · Groq · OpenAI · Anthropic · Streamlit · Docker · Loguru · Pytest

---

### 🧠 Fine-Tuning — [FinReasoner](https://huggingface.co/fcyber/FinReasoner-qwen2.5-14b-instruct)

A domain-specialized financial reasoning model. Not a chatbot, not a summarizer — a model trained to do the hard part of equity research: connecting a metric change to a root cause to a forward implication, grounded in evidence, without hallucinating.

**What makes it different from prompt-engineering a general model:** The dataset was purpose-built over 40,000 LLM calls through a multi-agent generator-auditor pipeline. Every training record links a numerical change to a textual cause to a market outcome. The model doesn't learn to sound like a financial analyst — it learns to reason like one.

|Dimension|Detail|
|---|---|
|Base model|Qwen 2.5 14B Instruct|
|Method|rsLoRA → SFT → DPO alignment|
|Training data|12,500 gold-standard records (score ≥ 80)|
|Universe|580 companies · 5 years · 10-K, 10-Q, 10-Q/A|
|Infrastructure|Lambda Labs A100 80GB|
|Framework|Unsloth · TRL · PEFT · BitsAndBytes (4-bit NF4)|
|Published|[fcyber/FinReasoner-qwen2.5-14b-instruct](https://huggingface.co/fcyber/FinReasoner-qwen2.5-14b-instruct)|

Three model checkpoints published: Phase 1 SFT · Phase 3 DPO · Final production

---

### ⚙️ MLOps — [mlops-hub](https://github.com/fcyber-labs/mlops-hub)

MLOps projects built the way production systems actually need to be built — not just model training scripts, but full pipelines with experiment tracking, orchestration, testing, and CI/CD.

Every project in this hub:

- Tracks all experiments in **MLflow** — parameters, metrics, artifacts, model registry
- Orchestrates multi-step pipelines with **Apache Airflow** — scheduled runs, dependency management, failure handling
- Uses **Redis** for caching, task queuing, and real-time feature serving where applicable
- Is fully containerized with **Docker** and **Docker Compose**, pushed to **Docker Hub**
- Has structured logging via **Loguru** and a test suite with **Pytest**
- Ships with a CI/CD pipeline — **GitHub Actions** or **GitLab CI** depending on the project

_More projects shipping. The first is live — link in the repo._

---

## How I build things

A few habits that show up across every project:

**Logging with Loguru, not print statements.** Structured logs from day one. When something breaks in production at 2am, you want context, not a traceback you can't reproduce.

**Pytest on everything.** Unit tests on the functions that matter, integration tests on the pipelines. Not 100% coverage for its own sake — tests on the things that actually break.

**Docker Compose for local development.** If it doesn't run in a container, it doesn't ship. Every project has a `docker-compose.yml` that spins up the full stack including dependencies. No "works on my machine" situations.

**MLflow for every experiment.** Parameters, metrics, artifacts, model versions — all tracked. Going back to a run from three weeks ago should take 10 seconds, not half an hour of git archaeology.

**CI/CD from the start.** Tests run on every push. Docker images build and push automatically on merge to main. Nothing gets deployed manually.

---

## Writing

I write about what I build — the real implementation details, the problems that took days to debug, the design decisions that look obvious in hindsight.

- [Why Integrating Apple's Ecosystem into a Local RAG Project Is Harder Than It Looks](https://medium.com/@fcyber/why-integrating-apples-ecosystem-into-a-local-rag-project-is-harder-than-it-looks-3949f9f03131)
- More pieces in progress on FinReasoner, the PPTX agent, and the MLOps stack

---

## Profiles

<div align="center">
[![Hugging Face|210](https://img.shields.io/badge/Hugging%20Face-fcyper-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black&labelColor=FFD21E&color=FFD21E)](https://huggingface.co/fcyper)[![Kaggle](https://img.shields.io/badge/Kaggle-fcyper-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white&labelColor=20BEFF&color=20BEFF)](https://www.kaggle.com/fcyper)[![Docker Hub](https://img.shields.io/badge/Docker%20Hub-fcyper-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=2496ED&color=2496ED)](https://hub.docker.com/r/fcyper)
[![Medium](https://img.shields.io/badge/Medium-fcyper-000000?style=for-the-badge&logo=medium&logoColor=white&labelColor=000000&color=000000)](https://medium.com/@fcyper)[![LinkedIn](https://img.shields.io/badge/LinkedIn-fcyper-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0077B5&color=0077B5)](https://www.linkedin.com/in/fcyper)
</div>




