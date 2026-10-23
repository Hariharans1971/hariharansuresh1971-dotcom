![Hariharan S. — Python, Backend & Applied AI](https://raw.githubusercontent.com/Hariharans1971/hariharansuresh1971-dotcom/main/assets/github-profile-banner.svg)

# Hariharan S. — Python, Backend & Applied AI

![Document Analysis CI](https://github.com/Hariharans1971/document_analysis/actions/workflows/tests.yml/badge.svg) [![Portfolio deployment](https://github.com/Hariharans1971/portfolio/actions/workflows/pages.yml/badge.svg)](https://github.com/Hariharans1971/portfolio/actions) [![Live-site verification](https://github.com/Hariharans1971/portfolio/actions/workflows/verify-live-site.yml/badge.svg)](https://github.com/Hariharans1971/portfolio/actions)

🌐 **Live portfolio:** [Vercel](https://portfolio1-tau-sandy.vercel.app/) · [GitHub Pages](https://hariharans1971.github.io/portfolio/) · [Source, CI and deployment status](https://github.com/Hariharans1971/portfolio/actions)

I'm a 2026 B.Tech Computer Science and Engineering (AI & ML) graduate based in Chennai, India. I build practical Python applications and focus on backend APIs, SQL/data workflows, retrieval-augmented generation (RAG), and AI-agent reliability. I value reproducible setup, test evidence, measured results, and honest limitations over unsupported production claims.

## Featured projects

### Agent Reliability Kit — AI-agent policy checks for CI

A local-first Python tool for recording JSONL traces, comparing agent runs, and enforcing declarative policy checks in CI. Includes a reusable GitHub Action and documented limitations.

- [Source code](https://github.com/Hariharans1971/Agent-Reliability-Kit-ARK-)
- [Policy contracts](https://github.com/Hariharans1971/Agent-Reliability-Kit-ARK-/blob/main/docs/POLICY_CONTRACTS.md)
- [CI checks](https://github.com/Hariharans1971/Agent-Reliability-Kit-ARK-/actions)


### 1. Document Analysis + RAG
A FastAPI document-question-answering demo with TXT/Markdown/PDF/DOCX ingestion, lexical retrieval, source-labelled passages, optional Gemini generation, API tests, and Docker setup.

- [Source code](https://github.com/Hariharans1971/document_analysis)
- [Architecture and trade-offs](https://github.com/Hariharans1971/document_analysis/blob/main/docs/ARCHITECTURE.md)
- [RAG guide and API details](https://github.com/Hariharans1971/document_analysis/blob/main/RAG_GUIDE.md)
- [Reproducible retrieval benchmark](https://github.com/Hariharans1971/document_analysis/blob/main/benchmarks/retrieval_eval.py)
- [CI runs](https://github.com/Hariharans1971/document_analysis/actions)

**Measured synthetic regression set (CI, 24 labelled queries):** Recall@1 = 0.833 (20/24), Recall@3 = 1.000 (24/24), MRR = 0.910. A distinct-term-overlap baseline scored Recall@1 = 0.833, Recall@3 = 0.958 (23/24), and MRR = 0.889. All six authored negative smoke queries returned no passages. These authored fixture results show regression behavior, not independent real-world quality or user impact.

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
Reproducible tabular ML evaluation with a fixed stratified holdout split and a majority-class baseline. In the latest recorded CI run on the tracked CSV (480 rows, 16 predictors), the Random Forest reached 0.8083 accuracy and 0.8118 macro-F1, versus 0.4417 accuracy and 0.2042 macro-F1 for the baseline. These are dataset-specific holdout metrics, not external validation or proof of causal relationships.

- [Source code and evaluation details](https://github.com/Hariharans1971/Student-Performance-ML-Project)
- [Latest CI run](https://github.com/Hariharans1971/Student-Performance-ML-Project/actions)

### 5. AltiusNxt Team Copilot — Local workflow demo
A local Python application demonstrating marketing/HR workflow prototypes, a local knowledge base, saved drafts, document upload, and role-aware access. It has unit tests, cross-role smoke checks, request-size validation, and a current-tree secret scan in GitHub Actions.

- [Source code](https://github.com/Hariharans1971/agent)
- [Security and deployment limitations](https://github.com/Hariharans1971/agent/blob/main/SECURITY.md)
- [Validation CI](https://github.com/Hariharans1971/agent/actions/workflows/validate.yml)

### 6. Zentrix AI
A Streamlit chatbot experiment with configurable Groq API integration, current-tree secret scanning, syntax validation, and safer error handling. Historical credential findings are still under remediation; do not consider its full Git history cleared yet.

- [Source code](https://github.com/Hariharans1971/Zentrix-AI)
- [Validation CI](https://github.com/Hariharans1971/Zentrix-AI/actions/workflows/validate.yml)

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
