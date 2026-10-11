## Hi, I'm Manuel 👋

Backend engineer based in Madrid. I work mostly in Python, on systems that
move and organise large amounts of data.

Right now I'm at **Deimos Space** (now part of Indra Group), working on the
backend of a satellite imagery archiving and cataloguing platform with ingestion
pipelines, geospatial search, and the APIs that Earth Observation scientists
use to find what they need. Before that I worked on API features at
**Santander (PagoFX)**, their international money transfer platform.

I have two Bachelor's degrees — Computer Science and Mathematics — and an
MSc in Data Science, all of which mostly means I enjoy problems where the
data model matters as much as the code.

**What I work with**

`Python` · `Docker` `Kubernetes` `Helm` · `PostgreSQL` `OpenSearch`
`RabbitMQ` · `STAC` `OGC` · `Linux` · `GitHub Actions`

**Learning by building**

`RAG` `pgvector` `Ollama` `LLM evaluation`

**A few things I've built on my own time**

[**Sentinel-1 RAG**](https://github.com/mmartinsie/sentinel1-rag) —
retrieval-augmented generation over ESA's Sentinel-1 documentation (SentiWiki
pages and technical PDFs), running fully local on an 8 GB GPU. Hybrid retrieval
with pgvector and keyword search, bge-m3 embeddings and a quantized Gemma 4 on
Ollama. Every answer cites the sections it comes from, in English or Spanish.
A 25-question retrieval eval puts the right section in the top 5 for 22 of them,
and the three misses are written up with their causes.

[**Madrid Flat Price Estimator**](https://github.com/mmartinsie/webscraping-fotocasa) —
end-to-end ML project: scraping, cleaning, k-fold cross-validation and a
baseline comparison published in the model card (the neural network lost to a
random forest, and the model card says so). Later extended with an LLM agent
using multi-tool function calling, including a hand-written agent loop
alongside the SDK one, instrumented for tokens and latency. 50+ tests,
GitHub Actions CI, ruff. Deployed on Streamlit.

[**lolScout**](https://github.com/mmartinsie/lolScout) — data analysis and
champion recommendation for League of Legends, built for my two Bachelor's
theses. Scraping, statistical modelling and time series.

**Currently interested in**

Data-intensive backends, API design, integrating messy external systems
into something coherent, and LLM systems grounded in real documentation.

📍 Madrid · 🇪🇺 EU citizen · Open to relocate to EU

[LinkedIn](https://www.linkedin.com/in/manuelmartinsierradeveloper/) · manumartin997@gmail.com
