# Hariharan S. — Python, Backend & AI/ML Developer

I’m a 2026 B.Tech Computer Science and Engineering (AI & ML) graduate based in Chennai, India. I build practical Python applications and am developing toward backend and AI systems engineering—with a focus on APIs, data workflows, retrieval-augmented generation (RAG), tests, and clear engineering trade-offs.

**Looking for:** Graduate / entry-level Software Engineer, Python Developer, Backend Developer, or AI Engineer roles.

**Core tools:** Python · SQL · FastAPI/Flask fundamentals · REST APIs · pandas · scikit-learn · MySQL · SQLite · Git/GitHub · Docker fundamentals

## Featured proof of work

### 1. Document Analysis + RAG
A FastAPI document-question-answering system with document ingestion, lexical retrieval, source-labelled passages, optional LLM generation, tests, and Docker setup.

- [Code](https://github.com/Hariharans1971/document_analysis)
- [Architecture and trade-offs](https://github.com/Hariharans1971/document_analysis/blob/main/docs/ARCHITECTURE.md)
- [RAG guide](https://github.com/Hariharans1971/document_analysis/blob/main/RAG_GUIDE.md)
- [CI runs](https://github.com/Hariharans1971/document_analysis/actions)

**Measured baseline:** Six fixed synthetic queries achieved Recall@1 = 1.00, Recall@3 = 1.00, and MRR = 1.00 in the smoke benchmark. This is a tiny synthetic fixture, not evidence of production retrieval quality.

**Known limitations:** lexical retrieval rather than embeddings, in-memory index, no authentication, no OCR, and not production-hardened.

### 2. Inventory Management System
A MySQL 8 project with 13 relational tables, an ER diagram, and 5,795 synthetic rows across inventory and business transaction tables.

- [Code and documentation](https://github.com/Hariharans1971/inventory-management-system)

### 3. ClinicDesk — appointment workflow demo
A learning project using FastAPI, SQLite, HTML/CSS/JavaScript, request validation, persistence, status filtering, and API tests.

- [Code](https://github.com/Hariharans1971/Clinic)
- [CI runs](https://github.com/Hariharans1971/Clinic/actions)

Educational demo only; it is not intended for real patient data.

### 4. Student Performance Prediction
A tabular ML exercise covering preprocessing, training, and classification evaluation.

- [Code](https://github.com/Hariharans1971/Student-Performance-ML-Project)

## Open-source contribution in review

[VueUse PR #5683](https://github.com/vueuse/vueuse/pull/5683) proposes support for element/component refs in `useTextDirection`, including computed CSS direction, reactive target changes, focused tests, and documentation. The pull request is open and not yet merged.

## How I work

- Prefer tests, reproducible setup, and meaningful documentation over unverified claims.
- Record limitations and trade-offs honestly.
- Keep credentials, private documents, and personal data out of source control.
- Use AI tools as assistants, then verify, test, and be prepared to explain every design decision.

## Experience

- **Python Development Intern — Cognifyz Technologies:** automation and data-processing tasks.
- **Machine Learning Intern — Cloudside Technologies:** ML work and Flask REST API exposure.

## Research

First-author IEEE ICECA 2025 paper: [“An Advanced Drug Mechanism of Action (MoA) Prediction Approach from Gene Expression using Transformers and XAI”](https://doi.org/10.1109/ICECA66444.2025.11383205). See the [matching Drug-MOA project](https://github.com/Hariharans1971/Drug-MOA-prediction).

## Contact

- GitHub: https://github.com/Hariharans1971
- Portfolio: https://portfolio1-tau-sandy.vercel.app/
- Alternate portfolio deployment: https://hariharans1971.github.io/portfolio/
- Portfolio validation and live HTTP checks: https://github.com/Hariharans1971/portfolio/actions
- LinkedIn: https://www.linkedin.com/in/hari-haran-b5aa50272/

> Profile setup note: this draft is ready to copy into the root `README.md` of a public repository named exactly `Hariharans1971`. The GitHub connector did not expose a repository-creation action, so it has not been published as the special profile README yet.
