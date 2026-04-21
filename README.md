# Vrushabh Mudda

**Data Engineer | AI Systems Builder | MS in AI & Business Analytics @ USF**

Building production-scale data pipelines and AI systems with 3+ years of industry experience across healthcare, enterprise, and government sectors. Specialized in ETL pipelines, multi-agent systems, RAG pipelines, and cloud-native data infrastructure.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vrushabh-mudda-6940131b6/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vrushabhmudda22@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://vrushabhmudda.github.io/portfolio-vmudda)

---

## 🎯 Current Focus

- **Graduate Researcher** @ University of South Florida — Healthcare AI & Business Analytics (May 2026)
- **Research Assistant** @ Cyber Florida — Critical infrastructure analytics (May–Aug 2025)
- **Industry Background** — Application Development Analyst @ Accenture (3+ years, Fortune 500)

---

## 🏆 Key Achievements

- ✅ **Production clinical AI** deployed on Google Cloud Run — 93 ICU patients, zero race conditions (SilentSurge, 2026)
- ✅ **0.07560 pAUC** on ISIC 2024 Kaggle Challenge — skin cancer detection, 3× above baseline
- ✅ **90%+ contextual accuracy** — multi-agent RAG system for Hindi-English medical translation
- ✅ **100M+ daily records** processed through enterprise data pipelines at Accenture
- ✅ **45% reduction** in ETL processing time through Python pipeline optimization
- ✅ **98% PII detection recall** with HIPAA-compliant spaCy NER privacy framework
- ✅ **$5M+ state program** funded through data-driven business case at Cyber Florida

---

## 🛠️ Technical Stack

**Data Engineering:** Python (PySpark, Pandas, NumPy) • SQL (T-SQL, PL/SQL) • ETL Pipelines • Apache Airflow • dbt • Apache Spark • Kafka • Hadoop

**Cloud & Platforms:** AWS (S3, Redshift, Glue, Lambda, CloudWatch) • Google Cloud Platform (BigQuery, Cloud Run) • Azure Synapse • Snowflake • Docker • Kubernetes

**AI/ML Frameworks:** PyTorch • TensorFlow • Keras • Scikit-learn • XGBoost • LangChain • HuggingFace • spaCy • OpenCV

**AI Specializations:**
- Multi-Agent Systems (Google ADK, ReAct framework, LangChain)
- RAG Pipelines (GPT-4, Gemini 2.5 Flash, Pinecone vector search)
- Deep Learning (CNN, Transfer Learning — InceptionV3, EfficientNetV2)
- NLP & Medical AI (HIPAA-compliant, PII masking, clinical domain)

**Data Governance & Quality:** HIPAA • GDPR • CCPA • Data lineage • dbt • Great Expectations

**Visualization:** Tableau • Power BI • Streamlit • Matplotlib • Seaborn

---

## 🎯 Looking for a specific skill set?

| Role | Core Skills |
|---|---|
| **Data Engineer** | Python, PySpark, SQL, ETL, Airflow, dbt, Spark, AWS, Snowflake, BigQuery, Kafka |
| **AI/ML Engineer** | PyTorch, LangChain, RAG, Multi-Agent Systems, GPT-4, Gemini 2.5, Google ADK |
| **Data Scientist** | Scikit-learn, XGBoost, statistical modeling, Kaggle (0.07560 pAUC), A/B testing |
| **Software Engineer** | FastAPI, React, PostgreSQL, Docker, Kubernetes, REST APIs, CI/CD |

---

## 🚀 Featured Projects

### 🏥 SilentSurge – Autonomous Multi-Agent ICU Sepsis Detection System
**Production clinical AI system processing real MIMIC-III data across 93 ICU patients**

Orchestrated a parallel multi-agent pipeline using Google ADK's ParallelAgent, simultaneously dispatching 4 specialized agents (VitalsWatcher, LabInterpreter, MedReviewer, EscalationAgent) against real ICU data — targeting 80% of preventable sepsis deaths.

**Key Achievements:**
- ✅ Zero race conditions across 93 concurrent patient pipelines via ParallelAgent architecture
- ✅ Eliminated critical clinical blind spot: beta-blocker-masked vitals missed by SIRS/qSOFA scoring
- ✅ Human-in-the-loop physician approval gate before every clinical escalation
- ✅ End-to-end production deployment on Google Cloud Run with PostgreSQL + Streamlit

**Architecture:**
- Google ADK ParallelAgent + LoopAgent self-correction pipeline
- Gemini 2.5 Flash (clinical reasoning) + LLaMA 3.3 70B on Groq (physician briefings)
- MIMIC-III: ChartEvents, LabEvents, Prescriptions
- PostgreSQL backend + Docker + Cloud Run + Streamlit dashboard

**Stack:** Python • Google ADK • Gemini 2.5 Flash • Groq • LLaMA 3.3 70B • PostgreSQL • Streamlit • Docker • Google Cloud Run

**[View Repository →](https://github.com/vrushabhmudda)**

---

### 🎤 VoiceRAG Medical Interpreter
**Real-time voice translation system for Hindi-English medical consultations**

Production-ready multi-agent RAG system enabling voice-to-voice medical translation with cultural context preservation and HIPAA-compliant privacy protection.

**Current Status:**
- ✅ Phase 1 Complete: Multi-agent text translation with 90%+ accuracy
- 🔄 Phase 2 In Progress: Voice input integration (Vapi.ai + Whisper STT)
- 📅 Phase 3 Planned: Voice output with 11Labs TTS (<500ms latency target)
- 📅 Phase 4 Planned: Clinical analytics dashboard

**Architecture Highlights:**
- 5 specialized AI agents (Coordinator, Intent Classifier, Translation, Safety, PII)
- Pinecone vector database with 1,536-dimensional embeddings
- 60+ medical documents in RAG knowledge base
- spaCy NER for automated PII detection (98% recall)
- ReAct reasoning framework for agent coordination
- Sub-second query response with SQLite conversation memory

**Stack:** Python • GPT-4o • Pinecone • spaCy • Whisper • Vapi.ai • FastAPI • Streamlit • SQLite

**[View Repository →](https://github.com/vrushabhmudda/voicerag-medical-interpreter)**

---

### 🩺 Melanoma Detection using Deep Learning (ISIC 2024 Kaggle)
**CNN-based skin cancer classification achieving 0.07560 pAUC — 3× above baseline**

Developed ensemble deep learning system processing 401,059 dermoscopic images from the ISIC 2024 Challenge dataset. Evaluated InceptionV3, ResNet50, and EfficientNetV2 architectures with transfer learning.

**Key Achievements:**
- **0.07560 pAUC** on public leaderboard | **0.07308** on private leaderboard
- InceptionV3 outperformed ensemble approaches — multi-scale modules capture dermoscopic features effectively
- Handled extreme 1000:1 class imbalance (benign:malignant) via minority oversampling
- Grad-CAM analysis confirmed model focuses on clinical ABCDE melanoma criteria
- 97.6% confidence on malignant classifications with proper feature attention

**Stack:** TensorFlow • Keras • InceptionV3 • ResNet50 • EfficientNetV2 • Scikit-Image • Albumentations • NumPy • Pandas

**[View Repository →](https://github.com/vrushabhmudda/Deep-Learning-project)**

---

### 🔐 Critical Infrastructure Analytics Platform
**Cybersecurity data analytics for Florida's 16 critical infrastructure sectors**

Engineered a comprehensive analytics platform processing government data across Florida, identifying 500+ critical assets and vulnerability patterns through automated pipelines and interactive dashboards.

**Key Achievements:**
- Built web scraping pipeline extracting data from 50+ government databases
- Improved data accuracy from 85% to 95% through automated validation framework
- Deployed Tableau dashboards with 20+ real-time KPIs reducing analysis time by 40%
- Implemented automated validation flagging 1,000+ data quality issues monthly
- Supported $5M+ state investment through data-driven business case
- Identified 200+ high-risk infrastructure assets requiring enhanced protection

**Stack:** Python • SQL • PostgreSQL • Tableau • Pandas • BeautifulSoup • Selenium • Docker • AWS EC2

**Duration:** May 2025 – Aug 2025 @ Cyber Florida

---

## 🔨 Currently Building

| Project | Status | ETA |
|---|---|---|
| SilentSurge v2 – Enhanced sepsis detection with expanded agent coverage | Active | Q2 2026 |
| VoiceRAG – Voice-to-voice medical translation (Phase 2) | Active | Q2 2026 |
| AWS Certified Data Engineer – Associate | In Progress | Q2 2026 |

---

## 💼 Professional Experience

**Application Development Analyst** | Accenture *(Promoted from Associate)*
*Oct 2021 – Aug 2024 | Bengaluru, India*
- Engineered SQL-based ETL pipelines processing 100M+ daily records with self-serve analytics for 200+ users
- Cut data processing time by 45% through Python multiprocessing ETL framework
- Compressed data delivery SLA from 24 hours to 2 hours via pipeline automation
- Designed star-schema dimensional models for enterprise data warehouse
- Built ML-driven incident classification system — 20% improvement in resolution time
- Prevented $500K+ in equipment failures via predictive maintenance models

**Research Assistant – Data Analytics** | Cyber Florida
*May 2025 – Aug 2025 | Tampa, FL*
- Engineered automated data pipelines processing critical infrastructure data across 16 sectors
- Built Tableau analytics dashboards identifying 200+ high-risk infrastructure assets
- Improved data accuracy from 85% to 95% through automated validation frameworks
- Optimized PostgreSQL queries reducing response time by 40%

**Network Engineering Intern** | Huawei Technologies
*Feb 2019 – Aug 2019 | Bengaluru, India*
- Developed automated Python + SQL aggregation pipeline for 1,000+ network base stations
- Achieved 15% throughput improvement and 20% downtime reduction through protocol optimization

---

## 🎓 Education

**M.S. in Artificial Intelligence and Business Analytics**
University of South Florida, Tampa, FL | Aug 2024 – May 2026 *(Expected)*

**B.E. in Electronics & Communication Engineering**
M.S. Ramaiah Institute of Technology, Bangalore, India | Aug 2015 – Jan 2020

---

## 📜 Certifications

- **SnowPro Core Associate** | Snowflake (2025)
- **AWS Certified Data Engineer – Associate** | In Progress (Q2 2026)
- **Deep Learning Specialization** | DeepLearning.AI (2022)

---

## 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=vrushabhmudda&theme=vue-dark&show_icons=true&hide_border=true&count_private=true)

---

## 🔬 Additional Projects

**AI-Powered Prompt Management Platform**
- Architected FastAPI microservices backend with Redis caching — sub-200ms p95 response times
- Reduced database query load by 58% through Redis caching layer over PostgreSQL
- Deployed on Kubernetes with auto-scaling, health checks, and AWS integration (S3, CloudWatch)
- **Stack:** Python (FastAPI) • React.js • PostgreSQL • Redis • Docker • Kubernetes • AWS

**Enterprise Incident Management Automation** *(Accenture)*
- Built Java Spring Boot APIs handling 500+ daily tickets with 98% system uptime
- Optimized SQL queries from 4.8s to 480ms through indexing and execution plan analysis
- Implemented CI/CD pipeline with Jenkins reducing deployment time from 4 hours to 45 minutes

---

💡 **Open to:** Data Engineer • AI/ML Engineer • Data Scientist • Software Engineer roles
📅 **Available:** May 2026
📍 **Location:** Tampa, FL | Open to remote & relocation

**Email:** [vrushabhmudda22@gmail.com](mailto:vrushabhmudda22@gmail.com)

*Last Updated: April 2026*
