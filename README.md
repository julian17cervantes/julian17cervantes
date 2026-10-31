<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=2563EB&center=true&vCenter=true&width=620&lines=Hi,+I'm+YOUR_NAME;CS+student+at+YOUR_SCHOOL;Backend+and+applied+ML;Looking+for+SWE+internships" alt="Hi, I'm YOUR_NAME. CS student at YOUR_SCHOOL. Backend and applied ML. Looking for SWE internships.">

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

## What I've built

**[Semantic Search](https://github.com/julian17cervantes/semantic-search)**
A search engine over Simple English Wikipedia (308k text chunks) that also answers factoid questions. I tuned a FAISS HNSW index to 99.7% recall@10 against exact search at about 20x the speed, and measured it against BM25 keyword search on 27 hand-labeled queries (semantic search won: 0.96 vs 0.70 hit@10). The answer step picks a span from the retrieved passages and withholds low-confidence answers. I froze its settings before writing 30 new questions, and it answered 22 of them correctly and withheld 7, with the limits written up in the README. Python, FastAPI, FAISS, Sentence-Transformers.

**[NYC Taxi Trip Duration](https://github.com/julian17cervantes/nyc-taxi-duration)**
Predicts taxi trip duration with LightGBM on 22M trips, using a time-based split. On a held-out month it cut error 10.2% below the best non-ML baseline, and the same recipe reproduced on a second year. Served with FastAPI and Docker. Python, DuckDB, LightGBM.

**[Course Compass](https://github.com/julian17cervantes/Course-Compass)**
A REST API for tracking courses and calculating GPA, with JWT authentication, per-user data isolation, a goal-GPA planner, and a final-exam calculator. Tested with Pytest and GitHub Actions, containerized with Docker, and deployed on Railway. Python, FastAPI, PostgreSQL, SQLAlchemy.

## Get in touch

[LinkedIn](https://www.linkedin.com/in/firstname-lastname) · [Email](mailto:you@example.com)
