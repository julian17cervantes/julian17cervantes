<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=2563EB&center=true&vCenter=true&width=620&lines=Hi,+I'm+Julian+Cervantes;CS+student+at+CSULB;Backend+and+applied+ML;Looking+for+SWE+internships" alt="Hi, I'm Julian Cervantes. CS student at CSULB. Backend and applied ML. Looking for SWE internships.">

![Programming Languages](https://img.shields.io/badge/Programming_Languages-555555?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning and AI](https://img.shields.io/badge/Machine_Learning_and_AI-555555?style=for-the-badge) ![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=for-the-badge) ![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![Data Storage and Retrieval](https://img.shields.io/badge/Data_Storage_and_Retrieval-555555?style=for-the-badge) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Backend and APIs](https://img.shields.io/badge/Backend_and_APIs-555555?style=for-the-badge) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MLOps and DevOps](https://img.shields.io/badge/MLOps_and_DevOps-555555?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Testing](https://img.shields.io/badge/Testing-555555?style=for-the-badge) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Frontend](https://img.shields.io/badge/Frontend-555555?style=for-the-badge) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

## What I've built

**[Semantic Search](https://github.com/julian17cervantes/semantic-search)**
A search engine over Simple English Wikipedia (308k text chunks) that also answers factoid questions. I tuned a FAISS HNSW index to 99.7% recall@10 against exact search at about 20x the speed, and measured it against BM25 keyword search on 27 hand-labeled queries (semantic search won: 0.96 vs 0.70 hit@10). The answer step picks a span from the retrieved passages and withholds low-confidence answers. I froze its settings before writing 30 new questions, and it answered 22 of them correctly and withheld 7, with the limits written up in the README. Python, FastAPI, FAISS, Sentence-Transformers.

**[NYC Taxi Trip Duration](https://github.com/julian17cervantes/nyc-taxi-duration)**
Predicts taxi trip duration with LightGBM on 22M trips, using a time-based split. On a held-out month it cut error 10.2% below the best non-ML baseline, and the same recipe reproduced on a second year. Served with FastAPI and Docker. Python, DuckDB, LightGBM.

**[Course Compass](https://github.com/julian17cervantes/Course-Compass)**
A full-stack course tracker: a FastAPI and PostgreSQL API with JWT authentication and per-user data isolation, plus a React frontend with a GPA summary and goal planner. Tested with Pytest and GitHub Actions, built with a multi-stage Docker image, and deployed on Railway. Python, React, FastAPI, PostgreSQL.

## Get in touch

[LinkedIn](https://www.linkedin.com/in/firstname-lastname) · [Email](mailto:you@example.com)
