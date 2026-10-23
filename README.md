# Hariharan S. | Python Developer • Backend • AI/ML

![Document Analysis CI](https://github.com/Hariharans1971/document_analysis/actions/workflows/tests.yml/badge.svg) [![Portfolio deployment](https://github.com/Hariharans1971/portfolio/actions/workflows/pages.yml/badge.svg)](https://github.com/Hariharans1971/portfolio/actions) [![Live-site verification](https://github.com/Hariharans1971/portfolio/actions/workflows/verify-live-site.yml/badge.svg)](https://github.com/Hariharans1971/portfolio/actions)

🌐 **Live portfolio:** [Vercel](https://portfolio1-tau-sandy.vercel.app/) · [GitHub Pages](https://hariharans1971.github.io/portfolio/) · [Source, CI and deployment status](https://github.com/Hariharans1971/portfolio/actions)

I am a 2026 B.Tech Computer Science and Engineering (AI & ML) graduate based in Chennai, India. I build practical Python applications and focus on backend APIs, data workflows, SQL, and retrieval-augmented generation (RAG). My portfolio emphasizes reproducible setup, test evidence, measured results, and honest limitations rather than unsupported production claims.

## Featured projects

### 1. Document Analysis + RAG
A FastAPI document-question-answering demo with TXT/Markdown/PDF/DOCX ingestion, lexical retrieval, source-labelled passages, optional Gemini generation, API tests, and Docker setup.

- [Source code](https://github.com/Hariharans1971/document_analysis)
- [Architecture and trade-offs](https://github.com/Hariharans1971/document_analysis/blob/main/docs/ARCHITECTURE.md)
- [RAG guide and API details](https://github.com/Hariharans1971/document_analysis/blob/main/RAG_GUIDE.md)
- [Reproducible retrieval benchmark](https://github.com/Hariharans1971/document_analysis/blob/main/benchmarks/retrieval_eval.py)
- [CI runs](https://github.com/Hariharans1971/document_analysis/actions)

**Measured baseline:** six fixed synthetic queries achieved Recall@1 = 1.00, Recall@3 = 1.00, and MRR = 1.00 in the documented smoke benchmark. This is a tiny synthetic test fixture, not evidence of production retrieval quality or user impact.

**Known limitations:** lexical retrieval rather than embeddings, in-memory index, no authentication, no OCR, and not production-hardened.

### 2. ClinicDesk — Full-stack appointment demo
FastAPI, SQLite, HTML/CSS/JavaScript, input validation, persistence, status filtering, and API tests. Includes a small REST API and interactive API documentation.

- [Source code](https://github.com/Hariharans1971/Clinic)
- [CI runs](https://github.com/Hariharans1971/Clinic/actions)

Educational demo only; do not use it for real patient data. Authentication, authorization, and clinical privacy controls are not implemented.

### 3. Inventory Management System
MySQL 8 database project with 13 relational tables and 5,795 synthetic rows across products, warehouses, purchasing, sales, payments, customers, employees, and stock movements.

- [Source code and documentation](https://github.com/Hariharans1971/inventory-management-system)

The row count describes the local demonstration dataset; it is not a performance or business-impact claim.

### 4. Student Performance Prediction
Tabular ML exercise covering data exploration, preprocessing, model training, and classification evaluation.

- [Source code](https://github.com/Hariharans1971/Student-Performance-ML-Project)

### 5. Zentrix AI
A Streamlit chatbot experiment with configurable Groq API integration.

- [Source code](https://github.com/Hariharans1971/Zentrix-AI)

## Open-source contribution

- [VueUse PR #5683 — support element refs in `useTextDirection`](https://github.com/vueuse/vueuse/pull/5683): proposes reading computed text direction from an element or Vue component ref while retaining the existing document-level API. The PR is open and awaiting upstream review/validation; it has not been merged.

## Skills

- **Languages:** Python, SQL, Java, JavaScript fundamentals
- **Backend:** Flask/FastAPI fundamentals, REST APIs, JSON
- **Data/ML:** pandas, NumPy, Matplotlib, scikit-learn
- **Databases:** MySQL, SQLite, PostgreSQL fundamentals
- **Tools:** Git, GitHub, Jupyter Notebook, Docker fundamentals, Azure AZ-900

## Experience

- **Python Development Intern — Cognifyz Technologies:** automation and data-processing tasks.
- **Machine Learning Intern — Cloudside Technologies:** machine-learning work and Flask REST API exposure.

## Research

First-author IEEE ICECA 2025 paper: [“An Advanced Drug Mechanism of Action (MoA) Prediction Approach from Gene Expression using Transformers and XAI”](https://doi.org/10.1109/ICECA66444.2025.11383205). The related research prototype is [Drug-MOA-prediction](https://github.com/Hariharans1971/Drug-MOA-prediction).

## Engineering principles

- Prefer readable code, reproducible setup, and useful tests.
- Report measured results only when they can be reproduced.
- Keep credentials and private data out of Git.
- Explain limitations instead of calling learning projects production-ready.
- Treat code-review and CI results as evidence; do not equate an open PR with an accepted contribution.

## Contact

- [GitHub](https://github.com/Hariharans1971)
- [LinkedIn](https://www.linkedin.com/in/hari-haran-b5aa50272/)
- [Email](mailto:hariharansuresh1971@gmail.com)

---

This repository is a project index. It is **not** the special GitHub profile README repository; that requires a repository named exactly `Hariharans1971`.
