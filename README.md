<h1 align="center">Hi, I'm Dev Shah</h1>

## ⚡️ About Me

I'm a B.S. student in **FinTech and Big Data Analytics** (Minor in CS) at Virginia Tech, graduating December 2027, interested in building **backend systems and data pipelines used in modern finance**.

I enjoy working at the intersection of:

- Software engineering & backend systems
- Quantitative finance & data pipelines
- AI-powered applications

My focus is on applying **core CS concepts (algorithms, systems, data pipelines)** to financial technology and quantitative engineering.

---

## 🚀 Current Focus

- 📊 Designing and implementing **real-time data pipelines** for financial and market data
- 🤖 Applying **machine learning models** to real-world datasets
- ⚙️ Building **high-performance systems** in C++ for risk and quantitative analysis
- 🧠 Strengthening fundamentals in **algorithms, data structures, and system design**
- 💼 Actively developing **ShinroFlow**, an AI-powered employment platform, with emphasis on API design, authentication, and CI/CD

---

## 💼 Experience

**AI Developer Intern — Miraivant Advisory LLC**
- Architected system design for ShinroFlow (7 Python/FastAPI modules)
- Built an AI resume-parsing engine and candidate-to-opportunity matching engine
- Secured REST APIs with JWT auth, Pydantic validation, Docker, and CI/CD

**Software Engineering Intern — K10 Index**
- Built Python backend services supporting 10K+ daily requests, 99.9% uptime
- Optimized SQL pipelines, cutting report generation time by 40%
- Collaborated with quant researchers on regression models and risk metrics

## 🛠️ Projects

### [Real-Time Data Ingestion & Analytics Pipeline](https://github.com/devrshah3/realtime-pipeline)
A high-throughput, fault-tolerant ingestion service that sustains **38K records/sec** using batched writes, schema validation, and dead-letter quarantine to isolate malformed records without blocking the batch. Uses a composite (symbol, timestamp) indexing strategy with a Redis caching layer to serve rolling-window statistics over REST. Architected as independently scalable FastAPI, PostgreSQL, and Redis services, containerized via Docker Compose, with pytest coverage across ingest and read paths.
**Stack:** FastAPI, PostgreSQL, Redis, Docker Compose, Python, pytest
**Result:** p99 read latency under 4ms, cutting mean read latency 18% via the caching layer.

### [High-Performance Multi-Asset Risk Engine](https://github.com/devrshah3/risk-engine)
A modular C++20 risk-computation engine designed for numerical analysis across 1,000+ entities. Implements multithreaded matrix operations and SIMD-vectorized kernels via Eigen to parallelize workload distribution. Independent modules handle correlation analysis, sensitivity calculations, and real-time aggregation, enabling concurrent execution across the risk pipeline.
**Stack:** C++20, Eigen, Multithreading, SIMD
**Result:** 35% throughput improvement through parallelized computation.

### [Global Soccer Prediction Engine](https://github.com/devrshah3/soccer-prediction-engine)
Built a production-grade soccer intelligence platform using 3,961 real matches and 5,102 player-match records across 80 competition-season datasets. Engineered leakage-safe team form, Elo, expected-goals, lineup, goalscorer, scoreline, goal-timing, live match-state, and award-ranking features using strictly chronological evaluation. Added concurrent daily batch inference, four evidence-based prediction tiers, historical event replay, FastAPI endpoints, and an interactive Streamlit dashboard.
**Stack:** Python, pandas, NumPy, scikit-learn, FastAPI, Streamlit, DuckDB, PyArrow, Pydantic, Plotly  
**Result:** Achieved 74.24% outcome accuracy and 0.601 log loss across a preliminary 50-match chronological live-replay holdout, compared with 0.827 log loss for the static pre-match baseline; all 63 automated tests passed.

## 🧰 Tech Stack

`Python` `C++` `SQL` `Go` `JavaScript` `FastAPI` `Flask` `PyTorch` `TensorFlow` `Docker` `AWS` `PostgreSQL` `MongoDB` `Redis`

## 📫 Connect

[LinkedIn](https://www.linkedin.com/in/devshah03) · devrshah3@gmail.com
