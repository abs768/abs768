# Bhavani Shankar Ajith

**Software Engineer • Data Systems • ML Infrastructure**  
MS Data Science @ Stony Brook (3.73 GPA) • Graduating May 2026

📧 bhavanishankar.ajith@stonybrook.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/abs768/) • [GitHub](https://github.com/abs768) • [Portfolio](https://abs768.github.io)

---

## 👨‍💻 What I Build

Production backend systems, data pipelines, and ML infrastructure. My work focuses on:
- **Microservices & APIs**: Spring Boot services processing 184K+ users with real-time validation
- **Data Infrastructure**: Event-driven pipelines handling 3K+ records with sub-minute latency
- **ML Systems**: GPU-optimized inference (250ms → <100ms) and RAG systems with vector search

**Tech Stack**: Java, Python, Spring Boot, Kafka, PostgreSQL, Snowflake, Docker, TensorRT

---

## 💼 Experience

### Software Engineer Intern • Navitas Business Consulting
*June 2024 – August 2024 | Herndon, VA*

Built production enrollment system serving 184K+ employees:
- **40% faster processing**: Automated legacy database sync with real-time eligibility validation
- **60% fewer data issues**: Built integration test suite with Testcontainers (85% coverage)
- **Zero-downtime migrations**: Led Liquibase adoption for version-controlled schema changes

**Stack**: Spring Boot, PostgreSQL, Liquibase, Testcontainers, Docker, JUnit

### Deep Learning Apprentice • NVIDIA Jetson AI Program
*May 2022 – October 2022*

Optimized vehicle damage detection pipeline for edge deployment:
- **60% faster inference**: 250ms → sub-100ms through TensorRT optimization + GPU preprocessing
- **40% less overhead**: Unified Memory architecture eliminating CPU-GPU transfer bottlenecks
- **Production deployment**: Dockerized service with health monitoring across edge devices

**Stack**: TensorFlow, TensorRT, CUDA, NVIDIA VPI, Docker, Nsight Systems

---

## 🚀 Featured Projects

### [Intelligent Document RAG](https://github.com/abs768/intelligent-doc-rag)
**Production-grade RAG system with microservices architecture**

Private document Q&A serving 100K+ chunks with vector similarity search:
- **Sub-100ms search**: Qdrant HNSW indexing (768-dim embeddings)
- **3-8s end-to-end latency**: Semantic chunking + local LLM (llama3.2) + PostgreSQL metadata
- **70% test coverage**: Integration tests with Testcontainers validating data isolation
- **Full auth flow**: JWT authentication, async processing, error handling

**Stack**: Spring Boot, Qdrant, PostgreSQL, React, Ollama, Docker, Testcontainers

**Architecture Highlights**:
- Semantic chunking (500-char, word-boundary aware) with nomic-embed
- RESTful APIs with controller-service-repository pattern
- Independent service scaling and testing

---

### [MarketPulse](https://github.com/abs768/MarketPulse-Real-Time-Stock-Pipeline)
**Real-time streaming analytics platform**

Event-driven pipeline processing 3K+ stock records across 600 companies:
- **Sub-minute latency**: Kafka streaming → MinIO → Snowflake (hours → <1min decision time)
- **96% reliability**: 25 Airflow DAG runs with automated retries and alerting
- **27x faster transforms**: 12min → 45s through query optimization (Bronze-Silver-Gold pattern)
- **Sub-second queries**: Materialized views powering 5 interactive dashboards

**Stack**: Kafka, Airflow, dbt, Snowflake, MinIO, Python, Streamlit

**Pipeline Features**:
- Minute-level ingestion with exponential backoff
- Incremental processing with data quality validation
- 31-second mean DAG duration

---

## 🛠️ Technical Skills
```
Languages          Java, Python, SQL, JavaScript, C++
Backend            Spring Boot, FastAPI, REST APIs, microservices, JWT auth
Data Engineering   Kafka, Airflow, dbt, ETL/ELT, data modeling
Databases          PostgreSQL, Snowflake, Qdrant (vector), query optimization
ML/AI              TensorFlow, TensorRT, PyTorch, RAG, CUDA, Ollama
DevOps             Docker, Testcontainers, Git, JUnit, CI/CD, Linux
Cloud              GCP (BigQuery, Cloud Functions), AWS (EC2, S3), MinIO
```

---

## 🎓 Education

**Stony Brook University (SUNY)** • *May 2026*  
MS in Data Science • GPA: 3.73/4.0

**SRM Institute of Science and Technology** • *June 2024*  
BTech in Computer Science (AI/ML) • GPA: 9.66/10.0

**Certifications**:
- Oracle OCI Generative AI Professional (2025)
- Oracle OCI Data Science Professional (2025)

---

## 📫 Let's Connect

Open to **Software Engineering** and **ML Infrastructure** roles for **Summer 2025** and **New Grad 2026**.

Interested in distributed systems, data infrastructure, and production ML systems.

📧 bhavanishankar.ajith@stonybrook.edu  
💼 [linkedin.com/in/abs768](https://www.linkedin.com/in/abs768/)
