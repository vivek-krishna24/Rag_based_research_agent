# Rag_based_research_agent
**# ShortResearchAgent – A Simple RAG-Based Research Agent

This project demonstrates the core logic of a **Retrieval-Augmented Generation (RAG)** system.
It combines web search, text embedding, similarity ranking, and extractive summarization to answer questions using content from multiple web pages.

---

## Features

1. **Retriever**
   - Performs web search using your query.
   - Fetches content from URLs.
   - Chunks long passages into manageable pieces.

2. **Ranker**
   - Converts passages into embeddings using `sentence-transformers`.
   - Computes similarity with the query using cosine similarity.
   - Ranks top passages for relevance.

3. **Generator (Extractive Summarizer)**
   - Splits top passages into sentences.
   - Ranks sentences by similarity to the query.
   - Generates a concise extractive summary with source references.**
