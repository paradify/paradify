# Guesmia

**AI engineer.** I build systems at the intersection of language models, data pipelines, and automation — things that run in production, not just notebooks.

My work tends to live in three areas: **LLM applications** (RAG pipelines, AI agents, document intelligence), **data infrastructure** (scrapers, ETL, analytics dashboards), and **applied ML** (predictive models, MLOps pipelines). Most of it is Python, most of it is for clients who need it to work reliably and keep working.

---

## What I build

**LLM applications**  
RAG systems, document Q&A, multi-step AI agents with tool use, Claude/OpenAI API integrations. Production-grade — with proper chunking, retrieval, caching, and error handling.

**Data pipelines & scraping**  
Scrapy spiders, Playwright-based scrapers, ETL pipelines into PostgreSQL or cloud warehouses, anti-detection at scale. Built for unattended operation over months.

**Machine learning, end-to-end**  
Feature engineering, XGBoost / scikit-learn models, hyperparameter tuning with Optuna, model serving via FastAPI, retraining pipelines. The full loop, not just the training step.

---

## Stack

```
Languages    Python · SQL
LLM          OpenAI API · Anthropic Claude · LangChain · LlamaIndex
ML           Scikit-learn · XGBoost · LightGBM · Optuna · Pandas · NumPy
Scraping     Scrapy · Playwright · BeautifulSoup · Requests
Data         PostgreSQL · MongoDB · Chroma · FAISS · Parquet
Infra        FastAPI · Docker · Linux · GitHub Actions
Viz          Plotly · Matplotlib · Grafana
```

---

## Selected Work

**[LexiQ — Legal Document Intelligence](https://github.com/username/lexiq)**  
RAG pipeline over 3,000+ legal contracts. PDFs parsed, chunked, embedded into a vector store. LangChain Q&A chain with source citations and risk clause flagging. Cut review time from 45 min to under 2 min per document.  
`LangChain` `RAG` `OpenAI` `Chroma` `FastAPI`

---

**[PriceLens — Competitive Price Intelligence](https://github.com/username/pricelens)**  
Distributed Scrapy scraper monitoring 50k+ SKUs across 12 competitor sites. Rotating proxy infrastructure, ETL into PostgreSQL, Grafana dashboard for the pricing team. Ran unattended for 14 months. Client measured a 9% margin improvement.  
`Scrapy` `Playwright` `PostgreSQL` `ETL` `Docker`

---

**[LeadForge — AI Lead Research Agent](https://github.com/username/leadforge)**  
LangChain agent that takes a company list, searches the web for contacts, extracts structured data, cross-references LinkedIn, and pushes enriched records to HubSpot CRM. Replaced 20 hrs/week of manual research for a 3-person sales team.  
`LangChain` `AI Agents` `OpenAI` `HubSpot API` `Web Scraping`

---

**[MarketPulse — Job Market Analytics](https://github.com/username/marketpulse)**  
Paginated data collection from the Freelancer.com API (1,000+ records per run), multi-dimensional filtering by client quality metrics, and a full analysis dashboard covering skill demand, budget distributions, and geographic breakdowns.  
`Python` `REST API` `Pandas` `Data Analysis` `Visualization`

---

**[ChurnGuard — Churn Prediction Pipeline](https://github.com/username/churnguard)**  
End-to-end MLOps for a SaaS client: PostgreSQL event log features, XGBoost + Optuna tuning, data drift detection, weekly retraining job, FastAPI serving. 78% precision on 30-day churn. CS team used it to cut monthly churn by ~2pp.  
`XGBoost` `Optuna` `FastAPI` `PostgreSQL` `Docker` `MLOps`

---

**[ReportAI — Automated Report Generation](https://github.com/username/reportai)**  
Claude API pipeline that ingests multi-source marketing data (GA4, Meta Ads, Google Ads), generates structured executive reports with narrative analysis, KPI tables, and recommendations. Reduced monthly reporting time from 6 hours to under 15 minutes.  
`Anthropic Claude` `Python` `GA4 API` `Data Viz` `Automation`

---

## Contact

**Email** — guesmia@outlook.tech
**Freelancer.com** — [freelancer.com/u/username](https://freelancer.com)

Open to freelance contracts in AI/ML engineering, data pipelines, and LLM applications.

---

<sub>All portfolio projects reflect real client work. Code samples and case study details available on request.</sub>
