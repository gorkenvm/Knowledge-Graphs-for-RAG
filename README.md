# Knowledge Graphs for RAG

This repository demonstrates how to integrate **Knowledge Graphs (KGs)** into **Retrieval-Augmented Generation (RAG)** systems.  

Through a series of Jupyter notebooks, you will learn how to:  
- Build a KG from text  
- Query it with Cypher  
- Expand it with new information  
- Use it to power a simple RAG chat demo  

---

## 📂 Contents

- `L1-query_with_cypher.ipynb` – Introduction to Cypher queries and graph interactions.  
- `L2-prep_text_for_RAG.ipynb` – Text preprocessing for RAG systems.  
- `L3-construct_kg_from_text.ipynb` – Entity and relationship extraction, KG construction.  
- `L4-add_relationships_to_kg.ipynb` – Adding and managing relationships in the KG.
- `L5-expand_the_kg.ipynb` – Expanding and enriching an existing KG.  
- `L6-chat_with_kg.ipynb` – KG-based RAG chat demo.  

---


## ⚙️ Installation

```bash
git clone https://github.com/gorkenvm/Knowledge-Graphs-for-RAG.git
cd Knowledge-Graphs-for-RAG

# create virtual environment (recommended)
python -m venv .venv && source .venv/bin/activate

# install dependencies
pip install -r requirements.txt


📖 Reference

This project is inspired by the DeepLearning.AI - Knowledge Graphs for RAG course.
[text](https://learn.deeplearning.ai/courses/knowledge-graphs-rag/?utm_source=chatgpt.com)