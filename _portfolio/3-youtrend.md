---
title: "Youtrend"
excerpt: "YouTrend is a knowledge graph-powered platform to search and explore the top 1000 YouTubers and their trending videos using semantic technologies."
collection: portfolio
---

YouTrend is a web-based application designed to help users explore the top 1000 YouTubers worldwide along with their trending videos. Built as part of a Knowledge Graph course project, YouTrend applies semantic technologies to offer a more intuitive, contextual, and interconnected search experience.

The application integrates two main datasets:
- **Top 1000 YouTube Channels** (from Kaggle), containing information on YouTuber ranks, subscribers, views, video count, and categories.
- **Trending YouTube Video Statistics** (from Kaggle), covering millions of daily trending videos from 113 countries.

Key features include:
- **Search by Name, Genre, or Country**: Enables users to filter YouTubers easily using semantic search.
- **YouTuber Detail View**: Displays information like channel rank, subscriber count, creation year, category, and related trending videos.
- **Video Detail View**: Presents trending history by country and date, along with detailed video metadata and visual assets.
- **Knowledge Graph Integration**: All data is modeled in RDF format and queried via SPARQL to enable linked, semantic navigation across entities.
- **Ontology Design in OWL**: A custom ontology was designed using Protégé to formally model classes (e.g., `channel`, `video`, `trendingInfo`), properties, and relationships among them.
- **Data Enrichment & Cleaning**: Involved scraping unique channel IDs, handling multilingual data, profile picture fetching, and cleaning inconsistent naming across datasets.

Architecture:
- **Frontend & Backend**: Developed with Django, integrating SPARQLWrapper to bridge the web application with the GraphDB RDF store.
- **GraphDB**: Hosted on Google Cloud Platform to manage RDF triples and enable SPARQL querying.
- **External Linking**: Integrated with Wikidata for resolving entities like countries and languages to improve completeness and consistency.

The project demonstrates how knowledge graphs can enhance user-facing applications with structured semantic data, improving both user experience and search precision.

More about this project:  
[Read the report](https://drive.google.com/file/d/1glgs_eZAUeVOyMMCBB0GyOMlnUX1TVFm/view?usp=sharing)
