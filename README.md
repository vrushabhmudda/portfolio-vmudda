# Vrushabh Mudda

**AI/ML Engineer** | **MS in AI & Business Analytics @ USF** | **Production ML Systems Specialist**

Building production-scale AI systems with 3+ years delivering solutions in healthcare, enterprise automation, and computer vision. Specialized in multi-agent systems, RAG pipelines, and deep learning.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vrushabh-mudda-6940131b6/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vmudda@usf.edu)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://vrushabhmudda.github.io/portfolio-vmudda)

---

## 🎯 Current Focus

- **AI Engineer** @ PromptOps AI Platform - Production ML infrastructure
- **Graduate Researcher** @ University of South Florida - Healthcare AI applications
- **Former Research Assistant** @ Cyber Florida - Critical infrastructure analytics

## 🏆 Key Achievements

- ✅ **0.07560 pAUC** on ISIC 2024 Kaggle Challenge (skin cancer detection)
- ✅ **Multi-agent RAG system** with 90%+ contextual accuracy for medical translation
- ✅ **100M+ daily records** processed through enterprise data pipelines at Fortune 500 company (Accenture)
- ✅ **98% PII detection recall** with HIPAA-compliant privacy framework
- ✅ **40% reduction** in data processing time through ETL optimization
- ✅ **20% improvement** in incident resolution using ML automation at Accenture

## 🛠️ Technical Stack

**AI/ML Frameworks:** TensorFlow • PyTorch • Keras • Scikit-learn • XGBoost • OpenCV • spaCy • Hugging Face

**Programming:** Python • SQL • R • Java • JavaScript • Bash

**Cloud & MLOps:** AWS (SageMaker, EC2, S3, Lambda, Glue) • Docker • Kubernetes • Apache Airflow • Snowflake

**Data Engineering:** Apache Spark • Hadoop • Pandas • NumPy • ETL Pipelines • Vector Databases (Pinecone)


**AI Specializations:** 
- Computer Vision (CNN, Transfer Learning, Object Detection)
- NLP & RAG Systems (GPT-4, embeddings, retrieval)
- Multi-Agent AI (ReAct framework, LangChain)
- Voice AI (Whisper, TTS, Vapi.ai - in progress)

**Visualization:** Tableau • Power BI • Matplotlib • Seaborn • Streamlit

## 🚀 Featured Projects

### 🎤 VoiceRAG Medical Interpreter (In Active Development)
**Real-time voice translation system for Hindi-English medical consultations**

Building production-ready multi-agent RAG system enabling voice-to-voice medical translation with cultural context preservation and HIPAA-compliant privacy protection. Currently implementing voice input integration with target completion March 2026 [file:16].

**Current Status:**
- ✅ Phase 1 Complete: Multi-agent text translation with 90%+ accuracy
- 🔄 Phase 2 In Progress: Voice input integration (Vapi.ai + Whisper STT)
- 📅 Phase 3 Planned: Voice output with 11Labs TTS (<500ms latency target)
- 📅 Phase 4 Planned: Clinical analytics dashboard

**Architecture Highlights:**
- 5 specialized AI agents (Coordinator, Intent Classifier, Translation, Safety, PII)
- Pinecone vector database with 1536-dimensional embeddings
- 60+ medical documents in RAG knowledge base
- spaCy NER for automated PII detection (98% recall)
- ReAct reasoning framework for agent coordination
- Sub-second query response with SQLite conversation memory

**Target Production Metrics:**
- <500ms voice-to-translation latency
- 100+ concurrent user sessions
- >95% transcription accuracy
- >98% medical term accuracy

**Stack:** Python, GPT-4o, Pinecone, spaCy, Whisper, Vapi.ai, FastAPI, Streamlit, SQLite

**Link:** [VoiceRAG Repository](https://github.com/vrushabhmudda/voicerag-medical-interpreter)

---

### 🩺 Melanoma Detection using Deep Learning (ISIC 2024)
**CNN-based skin cancer classification achieving 0.07560 pAUC on Kaggle Challenge**

Developed ensemble deep learning system processing 401,059 dermoscopic images from ISIC 2024 Challenge dataset [file:19]. Evaluated InceptionV3, ResNet50, and EfficientNetV2 architectures with transfer learning, achieving 3× better performance than alternative models on competition metric.

**Key Achievements:**
- **Competition Performance:** 0.07560 pAUC (public leaderboard), 0.07308 (private)
- **Model Selection:** InceptionV3 outperformed ensemble approaches
- **Data Challenge:** Handled extreme 1000:1 class imbalance (benign:malignant ratio)
- **Clinical Validation:** Grad-CAM analysis confirmed model focuses on ABCDE melanoma criteria
- **High Confidence:** 97.6% confidence on malignant classifications with proper feature attention

**Technical Implementation:**
- Transfer learning with ImageNet pretrained weights
- Architecture-specific preprocessing (299×299 for InceptionV3, 224×224 for ResNet/EfficientNet)
- Minority oversampling and balanced class weighting
- Data augmentation (rotation, zoom, flips, brightness)
- Stratified 80/20 train-validation split
- Early stopping and learning rate reduction
- Grad-CAM interpretability analysis validating clinical relevance

**Ensemble Analysis:** Single InceptionV3 outperformed weighted ensemble combinations, demonstrating multi-scale inception modules effectively capture dermoscopic features at varying lesion sizes and textures [file:19].

**Stack:** TensorFlow, Keras, InceptionV3, ResNet50, EfficientNetV2, Scikit-Image, Albumentations, NumPy, Pandas

**Link:** [Deep Learning Project](https://github.com/vrushabhmudda/Deep-Learning-project)

---

### 🔐 Critical Infrastructure Analytics Platform
**Cybersecurity data analytics system for Florida's critical infrastructure**

Engineered comprehensive analytics platform processing data from 16 critical infrastructure sectors across Florida, identifying 500+ critical assets and vulnerability patterns through automated data pipelines, SQL optimization, and interactive dashboards [file:14].

**Key Achievements:**
- Built web scraping pipeline extracting data from 50+ government databases
- Improved data accuracy from 85% to 95% through validation framework
- Deployed Tableau dashboards with 20+ real-time KPIs reducing analysis time by 40%
- Implemented automated validation flagging 1,000+ data quality issues monthly
- Optimized PostgreSQL queries achieving 40% faster response times
- Supported $5M+ state investment through data-driven business case
- Identified 200+ high-risk infrastructure assets requiring enhanced protection

**Technical Implementation:**
- Python web scraping (BeautifulSoup, Selenium) and REST API integration
- SQL ETL pipelines with automated data validation
- PostgreSQL database with optimized indexing and geospatial queries
- Interactive Tableau dashboards with drill-down capabilities
- Docker deployment on AWS EC2 with 99.5% uptime

**Stack:** Python, SQL, PostgreSQL, Tableau, Pandas, Matplotlib, BeautifulSoup, Selenium, Docker, AWS

**Duration:** May 2025 - Aug 2025 @ Cyber Florida

## 💼 Professional Experience

**AI Engineer** | PromptOps AI Platform  
*Aug 2025 - Dec 2025*
- Developing production AI systems and prompt optimization infrastructure
- Implementing MLOps pipelines for model deployment and monitoring
- Building scalable prompt management platform with microservices architecture

**Research Assistant - Data Analytics** | Cyber Florida  
*May 2025 - Aug 2025*
- Engineered automated data pipelines processing critical infrastructure data across 16 sectors
- Built Tableau analytics dashboards identifying 200+ high-risk infrastructure assets
- Improved data accuracy by 10% through automated validation and quality frameworks
- Optimized database queries reducing response time by 40%

**Application Development Analyst** | Accenture (Promoted from Associate)  
*Oct 2021 - Aug 2024*
- Developed ML-driven incident management systems processing 100M+ daily records
- Built predictive maintenance models preventing $500K+ in equipment failures
- Optimized SQL data pipelines reducing processing time by 45% through parallel execution
- Implemented real-time KPI dashboards reducing decision-making time by 35%
- Designed dimensional data models (star schema) for enterprise data warehouse
- Achieved 20% improvement in incident resolution time through intelligent automation

**Network Engineering Intern** | Huawei Technologies  
*Feb 2019 - Aug 2019*
- Developed automated data aggregation pipeline for 1,000+ network base stations
- Achieved 15% throughput improvement and 20% downtime reduction through protocol optimization
- Built Python-based network performance analysis system

## 🎓 Education & Certifications

**Master of Science in AI & Business Analytics**  
University of South Florida, Tampa, FL | *Aug 2024 - May 2026* (Expected)

**Bachelor of Engineering in Electronics & Communication**  
M.S. Ramaiah Institute of Technology, Bangalore, India | *Aug 2015 - Jan 2020*

**Certifications:**
- **SnowPro Core Associate** | Snowflake (2025)
- **AWS Machine Learning Specialty** (In Progress - March 2026)
- **AWS Data Engineering Associate** (In Progress - April 2026)
- **Deep Learning Specialization** (2022))

## 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=vrushabhmudda&theme=vue-dark&show_icons=true&hide_border=true&count_private=true)

## 🔬 Additional Projects

### Enterprise Incident Management Automation
- Built Java Spring Boot APIs handling 500+ daily tickets with 98% uptime
- Optimized SQL queries from 2s to 200ms through indexing and execution plans
- Implemented CI/CD pipeline with Jenkins reducing deployment time by 87%

### AI-Powered Retail Forecasting
- Processed 500GB+ sales data with Apache Spark forecasting models
- Built analytics dashboard with 20+ KPIs reducing manual analysis by 40%
- Designed scalable ETL pipeline for multi-source data integration

---

💡 **Open to:** Machine Learning Engineer, AI Engineer, Data Scientist, Data Engineer roles  
📅 **Available:** May 2026  
📍 **Location:** Tampa, FL | Open to relocation 

**Email:** vmudda@usf.edu | vrushabhmudda22@gmail.com

*Last Updated: January 2026*

