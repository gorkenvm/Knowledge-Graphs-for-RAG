# 📘 Knowledge-Graphs-for-RAG

**Implementation and demonstration of Knowledge Graphs for Retrieval-Augmented Generation (RAG).**

---

## 📌 Project Overview

This repository showcases how to integrate **Knowledge Graphs** with **RAG systems** to enhance structured knowledge representation and improve semantic search.  
The notebooks guide you step by step, from querying with Cypher to building knowledge graphs from text and finally integrating them into a chatbot interface.

---

## 📊 Workflow

The architecture of the project is illustrated below:

```mermaid
flowchart TD
    A[Text Documents] -->|Preprocessing| B[Prep Text for RAG]
    B -->|Entity Extraction| C[Construct Knowledge Graph]
    C -->|Add Relationships| D[Expanded Knowledge Graph]
    D -->|Integration| E[Chat with KG + RAG]
    E -->|Responses| F[User]
```

---
