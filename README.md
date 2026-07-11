<h1 align="center">Hi there, I'm Kunal Gaikwad 👋</h1>

<h3 align="center">Data Scientist — Generative AI & Agentic AI | LLMs • RAG • Agentic Systems • NLP</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/kunal-gaikwad06/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:Kunal.gaikwad06@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" /></a>
  <a href="https://twitter.com/kunal8928"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=kunalg06&style=for-the-badge&color=brightgreen" />
</p>

---

## 🧠 About Me

🎓 **MSc Artificial Intelligence (Distinction)** — Sheffield Hallam University, UK
💼 **4+ years** of end-to-end ML engineering experience across NLP, computer vision, and cloud-deployed inference
🔍 Currently building **Generative AI and Agentic AI systems** at Synechron — LLM orchestration, MCP-based tool integration, and enterprise-scale AI for financial services clients
📍 Based in **Bengaluru, India** | 🗺️ **Open to senior AI/Data Science roles across the UK, Europe, UAE, Canada, and New Zealand — remote or relocation**

Previously at **Quantiphi**, where I delivered NLP automation pipelines that improved claim adjudication efficiency by 80%, and at **Winjit Technologies**, where I built computer vision systems contributing to ~50% revenue growth for enterprise clients including Mahindra & Mahindra.

---

## 🚀 Featured Projects

### 🇬🇧 [AI Sponsorship Job Acquisition Platform](https://github.com/kunalg06/AI-Sponsorship-Job-Acquisition-Platform)
> Personal automation pipeline for a UK Skilled Worker sponsorship search — reads public government data and drafts content; every risky action (applying, sending, messaging) stays a manual human click by design
- MCP server (`src/mcp_server/`) exposing the pipeline as four tools — `check_sponsor`, `check_salary_threshold`, `track_application`, `list_applications` — so an MCP client like Claude Desktop can query and update the search conversationally, verified end-to-end against a real client
- Thin-wrapper MCP architecture: zero business logic in the tool layer, connection-per-call SQLite access, and project-root-anchored paths — built to survive an MCP client spawning the server from an arbitrary working directory
- UK sponsor-register ingestion with name normalization (trading names, LTD/LIMITED/LLP/PLC suffix variants) against the real gov.uk register, plus SOC-code salary-threshold checks against actual government thresholds
- Documented spec-and-review discipline: intent contract, I/O edge-case matrix, and an adversarial review triage log per feature; 122 passing tests

### 🎯 [hire-signal](https://github.com/kunalg06/hire-signal)
> Full-stack hiring-evaluation platform that assesses candidates on real-world AI-assisted coding competency, not just algorithmic recall
- Candidates solve challenges in an isolated Docker + browser-VS-Code environment with Gemini CLI access; full workspace and AI-session transcript are captured on submit
- LLM-driven 8-dimension scoring (problem decomposition, debugging with AI, architecture decisions, and more), with hire thresholds enforced in Python, not by the LLM's own claim
- Employer dashboard with radar-chart candidate comparison, human override/flag workflow, and an append-only audit trail
- 11-table SQLite schema, 199 passing tests (fully mocked LLM/Docker), and a benchmarking suite run against the real Gemini API and real Flask routes — with documented, file-referenced production bottlenecks (N+1 query, connection pooling, single-worker WSGI) found via that benchmarking, not guessed

### 🛒 [Retail Insights Assistant](https://github.com/kunalg06/retail-insights-assistant)
> GenAI-powered conversational analytics using LLM-driven SQL generation and multi-agent workflows
- Natural-language querying over retail datasets via schema-aware SQL generation
- Multi-agent reasoning with conversation memory for contextual queries
- Designed for 100GB+ dataset scale

### 📚 [RAG Knowledge Assistant](https://github.com/kunalg06/rag-knowledge-assistant)
> End-to-end Retrieval-Augmented Generation system for document Q&A
- LangChain + OpenAI Embeddings + FAISS vector database
- Document ingestion, chunking, vector indexing, and grounded LLM responses with citations
- FastAPI backend for scalable document question-answering

### 🤖 [Autonomous Data Science Agent](https://github.com/kunalg06/Autonomous-Data-Science-Agent)
> AI agent that auto-analyzes CSV datasets using Claude AI + Machine Learning
- Plain-English queries → automated ML analysis pipeline
- Intelligent tool selection for classification, regression, and clustering

### 📄 [AI Resume Parser](https://github.com/kunalg06/Resume-Parser-AI)
> NLP-based resume parsing with SpaCy NER and rule-based extraction
- Parses PDF, DOCX, TXT resumes into structured JSON/CSV
- Section-aware extraction for skills, experience, and education
- FastAPI batch-processing API

---

## 🛠️ Tech Stack

**LLM & Agentic AI**
![MCP](https://img.shields.io/badge/Model_Context_Protocol-000000?style=flat&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![SpaCy](https://img.shields.io/badge/SpaCy-09A3D5?style=flat&logo=spacy&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=flat&logo=huggingface&logoColor=black)

**Languages & ML Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

**Cloud & Deployment**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Data & Tools**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## 💼 Work Experience

| Role | Company | Period |
|------|---------|--------|
| Data Scientist — Generative AI & Agentic AI | Synechron, Bengaluru | Mar 2026 – Present |
| Research Associate | Sports Engineering Research Group, Sheffield Hallam | Jul – Sep 2023 |
| Machine Learning Engineer | Quantiphi Analytics, India | May 2021 – Aug 2022 |
| Software Engineer (CV & NLP) | Winjit Technologies, India | Aug 2018 – Apr 2021 |

---

## 🎓 Education

- **MSc Artificial Intelligence (Distinction)** — Sheffield Hallam University, UK (2022 – 2023)
- **Post-Graduation Diploma, Machine Learning and AI** — IIIT Bangalore (2020 – 2021)
- **B.E., Information Technology** — Sinhagad Technical Education Society's COE (2013 – 2018)

## 📜 Certifications

- ☁️ AWS Certified Developer – Associate
- 🤖 IBM Generative AI for Data Scientists Specialization — Coursera
- 📈 Structuring Machine Learning Projects
- 🐍 HackerRank Certified Python
- ⛓️ Introduction to Blockchain
- 🧠 Machine Learning and AI

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=kunalg06&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/409ba5/kunalg06" alt="Kunal's GitHub Contribution Chart" />
</p>

---

<p align="center">
  💬 <i>Open to senior AI/Data Science roles across the UK, Europe, UAE, Canada, and New Zealand — remote or relocation.</i><br/>
  📩 Reach me at <a href="mailto:Kunal.gaikwad06@outlook.com">Kunal.gaikwad06@outlook.com</a>
</p>
