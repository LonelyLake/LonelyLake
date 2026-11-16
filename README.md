**Junior Data Engineer** 

Focusing on ETL/ELT pipelines, data modeling, and data validation.

Open to Junior Data Engineer roles in Poland (hybrid).

---

### Background & Certifications

- **Current Role:** AI Engineer Intern @ Łukasiewicz – AI (*ongoing, until Jan 2027*)
- **Education:** B.E. Informatics @ Silesian University of Technology (*Oct 2023 – Jan 2027*)
- **Certification:** [DataCamp Data Engineer Associate](https://www.datacamp.com/certificate/DEA0010088572223)

### Tech Stack & Tools

* Languages: Python, SQL (PostgreSQL, DuckDB), Bash
* Data Engineering: ETL/ELT Pipelines, Medallion Architecture, Dimensional Modeling, Data Validation, Parquet
* Engineering & Tooling: Docker / Docker Compose, Git (GitHub Flow), Linux, `uv`, pytest, `just`
* AI / Automation: LLM function calling (Ollama), RAG (ChromaDB), Playwright, FastAPI

### Featured Projects

#### [SmogWatch Poland](https://github.com/LonelyLake/smog-watch-poland)
Air quality data pipeline (OpenAQ API → Parquet Bronze/Silver → PostgreSQL)

* Built an ETL pipeline with local Bronze/Silver Parquet layers, YAML sensor configuration, and one-command runs via `just`.
* Implemented retries with exponential backoff for API ingestion and validation of physical value ranges (including sentinel values); pytest tests cover ingestion and validation.
* Idempotent loading into PostgreSQL (composite primary key, `ON CONFLICT DO NOTHING`) and SQL analytics (e.g. WHO PM2.5 exceedances).

#### [Retailrocket Recommender System](https://github.com/scarlet-enlight/retailrocket-recommender-system)
Engineering thesis, team of 3: simulated e-commerce shop with Apriori-based recommendations (~2.7M events)

* Data engineering part: multi-schema PostgreSQL design with Docker Compose; building a Python/DuckDB ELT pipeline that prepares basket data for the ML service.
* GitHub Flow with a protected `main` branch, pull requests and code reviews.

#### [SQL Data Engineering & Market Analysis](https://github.com/LonelyLake/sql-data-engineering-projects)
Course project (based on Luke Barousse's SQL course), extended with a Poland-specific market analysis

* Star-schema data warehouse with incremental `MERGE` patterns and analytical data marts in DuckDB.
* Added an analysis of Junior DE skill demand and salaries in Poland vs. the global market.

---

### Connect with me

- **LinkedIn:** [linkedin.com/in/starlitsky](https://linkedin.com/in/starlitsky)
