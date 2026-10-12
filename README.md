# Muhammad Qazi

MS Computer Science, Johns Hopkins University (2026) · Laurel, MD · U.S. Citizen

I build backend services in Python: REST APIs, PostgreSQL, Redis, background workers, automated testing, and deployment on AWS. Before my MS, I spent two years at Morgan Stanley automating daily P&L reporting for the Fixed Income Rates desks.

## Projects

### [DocSearch](https://github.com/mqazi3/docsearch-api) · [live demo](https://docsearch.mqazi98.com)
Question-answering API over long documents. Hybrid search (pgvector + Postgres full-text, merged with reciprocal rank fusion), answers that must cite a page for every claim, and refusals when the document doesn't cover the question. Retrieval MRR@10 went from 0.716 to 0.807 through A/B-tested changes, with 0 unsupported citations across 42 evaluated answers. Background ingestion with RQ, API keys and Redis rate limits, 92 tests in CI, and auto-deploy to AWS EC2 (Terraform, Docker Compose) through GitHub OIDC for about $5/month.

### [FinFlow API](https://github.com/mqazi3/finflow-api)
Financial transaction backend: FastAPI, PostgreSQL, Redis, Docker. 21 routes with JWT auth and user-scoped data, exact-decimal money, SQL-aggregate analytics with cache invalidation, Alembic migrations, and a 47-test pytest suite in GitHub Actions. Previously deployed on AWS ECS/Fargate with RDS and ElastiCache.

### [Discord Music Bot](https://github.com/mqazi3/discord-music-bot)
Asynchronous Python bot for voice-channel audio playback (discord.py, yt-dlp, FFmpeg). Used across 2 servers with 165+ members; previously deployed on AWS ECS/Fargate.

## Skills

**Languages:** Python, SQL, Java · familiar with C++, JavaScript/TypeScript, Go, ARM Assembly

**Backend & Data:** FastAPI, REST APIs, Pydantic, SQLAlchemy, Alembic, PostgreSQL, pgvector, MySQL, Redis, RQ, JWT

**AI & Search:** OpenAI API, retrieval-augmented generation (RAG), hybrid search, retrieval evaluation (MRR, hit@k)

**Cloud & DevOps:** AWS (EC2, ECS/Fargate, ECR, RDS, ElastiCache, Route 53, IAM, SSM, CloudWatch), Terraform, Docker, Docker Compose, GitHub Actions, Linux

**Testing & Tools:** pytest, ruff, pre-commit, Git

## Currently

Open to backend and full-stack software engineering roles. Willing to relocate anywhere in the U.S.

[LinkedIn](https://www.linkedin.com/in/muhammadqazi1/) · muhammadqazi1998@gmail.com
