---
title: "Təmu Search Engine"
excerpt: "A FastAPI + Elasticsearch-based search engine with support for neural reranking and LLM-enhanced result summaries."
collection: portfolio
---

Temusearch is a lightweight search engine built using FastAPI and Elasticsearch, designed to support ranked information retrieval and enhanced result summaries using large language models (LLMs).

The application supports both keyword-based and semantic search, and allows reranking of results for improved relevance. It is currently configured to work with a movie plot dataset (MPST), where users can query for movie themes and receive relevant results along with their relevance scores.

Key features include:

- **Elasticsearch-based indexing** with support for custom fields and movie metadata
- **FastAPI backend** with modular architecture and endpoint for search queries
- **Reranking capability** using neural models for improved result quality
- **LLM-enhanced summaries** that explain why each result is relevant based on user queries
- **Local and public deployment support**, including Docker Compose for containerized environments
- **Custom scripts** for data preparation (`convert_mpst.py`) and indexing (`index_mpst.py`)

The backend is modular and extensible, making it easy to plug in different datasets or models, and suitable for experimentation in information retrieval and LLM-based relevance explanation.

Source Code:
- [Backend Repository (FastAPI)](https://github.com/nabilmuafa/be-temu-search-engine)  
- [Frontend Repository (React)](https://github.com/aldenluthfi/fe-temu-search-engine)

A recorded demo of the system is available on YouTube:  
[Watch the video](https://youtu.be/Kf_xEvmCBJw)
