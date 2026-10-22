# Hariharan S. | Python Developer • Backend • AI/ML

![Document Analysis CI](https://github.com/Hariharans1971/document_analysis/actions/workflows/tests.yml/badge.svg) [![Portfolio deployment](https://github.com/Hariharans1971/portfolio/actions/workflows/pages.yml/badge.svg)](https://github.com/Hariharans1971/portfolio/actions)

I am a 2026 B.Tech Computer Science and Engineering (AI & ML) graduate in Chennai, India. I build practical Python projects and am strengthening my skills in REST APIs, SQL, full-stack development, and retrieval-augmented generation (RAG).

## Featured projects

### 1. Document Analysis + RAG
FastAPI document Q&A demo with TXT/Markdown/PDF/DOCX ingestion, lexical retrieval, source-labelled passages, optional Gemini generation, API tests, and Docker setup.

- [Source code](https://github.com/Hariharans1971/document_analysis)
- [Architecture and setup](https://github.com/Hariharans1971/document_analysis/blob/main/RAG_GUIDE.md)
- [Architecture decisions and trade-offs](https://github.com/Hariharans1971/document_analysis/blob/main/docs/ARCHITECTURE.md)
- [Reproducible retrieval benchmark](https://github.com/Hariharans1971/document_analysis/blob/main/benchmarks/retrieval_eval.py)
- [CI runs](https://github.com/Hariharans1971/document_analysis/actions)

**Synthetic benchmark baseline:** the six fixed demo queries achieved Recall@1 6/6, Recall@3 6/6, and MRR 1.000 in CI. This only checks expected behavior on a tiny synthetic fixture; it is not a claim about production accuracy or user impact.

**Current limitations:** lexical retrieval (not embeddings), in-memory document index, no authentication, no OCR, and not production-hardened.

### 2. ClinicDesk — Full-stack appointment demo
FastAPI, SQLite, HTML/CSS/JavaScript, request validation, persistence, and API tests.

- [Source code](https://github.com/Hariharans1971/Clinic)
- [CI runs](https://github.com/Hariharans1971/Clinic/actions)

Educational demonstration only; do not use it for real patient data.

### 3. Inventory Management System
MySQL database project with 13 relational tables, synthetic CSV data, an ER diagram, and SQL reports.

- [Source code](https://github.com/Hariharans1971/inventory-management-system)

### 4. Student Performance Prediction
Tabular machine-learning exercise covering data exploration, preprocessing, training, and classification evaluation.

- [Source code](https://github.com/Hariharans1971/Student-Performance-ML-Project)

### 5. Zentrix AI
Streamlit chatbot experiment using the Groq API.

- [Source code](https://github.com/Hariharans1971/Zentrix-AI)

## Skills

- **Languages:** Python, SQL, Java, JavaScript fundamentals
- **Backend:** Flask/FastAPI fundamentals, REST APIs, JSON
- **Data/ML:** pandas, NumPy, Matplotlib, scikit-learn
- **Databases:** MySQL, SQLite, PostgreSQL fundamentals
- **Tools:** Git, GitHub, Jupyter Notebook, Docker fundamentals, Azure AZ-900

## Experience

- **Python Development Intern — Cognifyz Technologies:** Python automation and data-processing tasks.
- **Machine Learning Intern — Cloudside Technologies:** machine-learning work and Flask REST API exposure.

## Research

First-author IEEE ICECA 2025 paper: “Risk-Aware Dynamic Inference for Balancing the Energy–Safety Tradeoff in Autonomous Driving Systems.” Use the official publication record for the full citation and experimental details.

## Engineering principles

- Prefer readable code, reproducible setup, and useful tests.
- Report measured results only when they can be reproduced.
- Keep credentials and private data out of Git.
- Explain limitations instead of calling learning projects production-ready.

## Contact

- [GitHub](https://github.com/Hariharans1971)
- [LinkedIn](https://www.linkedin.com/in/hari-haran-b5aa50272/)
- [Email](mailto:hariharansuresh1971@gmail.com)

---

This repository is a project index. It is **not** the special GitHub profile README repository; that requires a repository named exactly `Hariharans1971`.
