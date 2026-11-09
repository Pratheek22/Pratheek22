
# Pratheek J Gowda

### Software Engineer | Backend Engineering | Distributed Systems

Computer Science undergraduate at **PES University, Bengaluru**, interested in designing scalable backend systems, distributed infrastructure, and reliable software platforms.

My experience spans backend engineering, distributed systems, event-driven architectures, storage systems, and applied AI research. I enjoy solving engineering problems involving system architecture, asynchronous communication, fault tolerance, data processing, and performance optimization.

- **Education:** B.Tech in Computer Science and Engineering, PES University
- **CGPA:** 9.05/10
- **Experience:** Flipkart, cHEAL Research Centre, PES University
- **Interests:** Backend Engineering, Distributed Systems, Infrastructure and Applied AI

---

## Technical Skills

**Programming Languages**

Java, Python, C, JavaScript, SQL

**Backend Engineering**

Spring Boot, Flask, REST APIs, Maven

**Distributed Systems & Messaging**

Apache Kafka, Apache Pulsar, RabbitMQ, Apache ZooKeeper, Apache Spark

**Databases & Data Platforms**

MySQL, MongoDB, Redis, Elasticsearch, Hadoop, HDFS, Apache Hive

**Infrastructure & Developer Tools**

Linux, Docker, Kubernetes, Git, GitHub, Postman

**AI & Machine Learning**

PyTorch, TensorFlow, YOLOv8, Hugging Face, NLP, Retrieval-Augmented Generation

---

## Professional Experience

### Software Development Engineer Intern | Flipkart
*May 2026 – July 2026 | Bengaluru, India*

- Engineered an asynchronous Apache Pulsar event pipeline across 6 file-processing workflows, correlating upload intent with downstream events for end-to-end observability.
- Validated event correlation against 200,000+ records, with measured telemetry overhead of 1.7% of processing time.
- Reworked filtered listing APIs from offset pagination to Elasticsearch `search_after` cursor pagination, eliminating the 10,000-result window constraint and enabling traversal of 200,000+ item seller catalogs.
- Implemented a cursor-paginated file metadata API with multi-filter querying and lifecycle-status tracking to support scalable UI listing and audit workflows.

### Research Intern | cHEAL Research Centre
*June 2025 – July 2025 | Bengaluru, India*

- Developed LexicAid, an agentic AI-based dyslexia support system integrating CNN-based handwriting classification, YOLOv8 spatial-feature extraction, and adaptive task recommendations.
- Implemented a Double Dueling Deep Q-Network (DQN) with prioritized experience replay to personalize learning interventions using a 6-dimensional learner state representation.
- Integrated Explainable AI techniques using Grad-CAM and Captum Saliency to improve model interpretability.
- Evaluated policy behaviour through multi-seed experiments, baseline comparisons, and 6D-versus-4D state-space ablation studies.
- Contributed to a research manuscript submitted to a peer-reviewed international journal and a published Indian patent application (IN202641012232).

### Teaching Assistant | PES University
*January 2026 – December 2026 | Bengaluru, India*

- Supported Microprocessor and Computer Architecture (MPCA) and Python laboratory sessions by explaining concepts and troubleshooting implementation issues.
- Evaluated vivas, laboratory assignments, and course projects.
- Guided students on implementation, design decisions, and technical problem-solving.

---

## Featured Projects

### Distributed Ensemble Learning Platform

**Java | Spring Boot | RabbitMQ | ZooKeeper | MySQL**

A distributed machine-learning orchestration platform coordinating model-training tasks across dataset partitions.

- Designed a master-worker architecture with one master and three workers.
- Implemented worker registration and failure detection using ZooKeeper ephemeral znodes.
- Used RabbitMQ acknowledgements and automatic re-queuing to recover unacknowledged tasks when workers fail.
- Designed extensible model adapters for Decision Tree, Random Forest, and Logistic Regression using Strategy and Factory patterns.
- Implemented 9 REST endpoints and applied 7 design patterns across the architecture.

### Mini HDFS — Distributed File Storage System

**Python | Flask | Distributed Storage**

A Hadoop-inspired distributed file system exploring storage replication, node monitoring, and failure recovery.

- Implemented chunk-based file storage with configurable replication.
- Developed UDP heartbeat mechanisms for worker-node health monitoring.
- Implemented automatic re-replication to handle node failures.
- Exposed file operations through Flask REST APIs.
- Built a monitoring dashboard to inspect node health and storage activity.

### Court RAG — Legal Research & Reasoning System

**Python | FAISS | Sentence Transformers | LLMs**

A retrieval-augmented legal research system designed to retrieve relevant statutes and case precedents from a corpus of legal documents.

- Built semantic retrieval pipelines over 2,900+ case files.
- Used Sentence Transformers and FAISS for embedding generation and top-k retrieval.
- Implemented specialized Fact Extractor, Prosecution, Defense, and Judge agents.
- Combined retrieved evidence with agent-based reasoning to generate structured arguments and final verdicts.

### Meta-Statistics — EPL Match Outcome Prediction

**Python | Machine Learning | Statistical Analysis**

A machine-learning project exploring English Premier League match outcome prediction using historical football statistics.

- Performed data preprocessing and feature engineering.
- Explored statistical relationships between match-related features and outcomes.
- Implemented and evaluated predictive models.

---

## Research & Publications

**LexicAid — Explainable Agentic AI System for Dyslexia Support**

- Research work conducted at cHEAL Research Centre.
- Published Indian patent application: `IN202641012232`.
- Research manuscript submitted to a peer-reviewed international journal.

---

## Areas of Interest

- Backend and Platform Engineering
- Distributed Systems and Event-Driven Architecture
- Database Internals and Storage Systems
- System Design and Scalability
- Fault Tolerance and Reliability Engineering
- Operating Systems and Computer Architecture
- AI Systems and Retrieval-Augmented Generation

---

## Connect

- **GitHub:** [Pratheek22](https://github.com/Pratheek22)
- **LinkedIn:** [Pratheek J Gowda](https://www.linkedin.com/in/pratheek-j-gowda-899712300/)
- **Email:** pratheek2245@gmail.com

---

*Building reliable systems, understanding them deeply, and continuously improving how they work.*
