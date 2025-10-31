# RAG-Insight

## Overview
A basic Retrieval-Augmented Generation (RAG) pipeline for contextual question-answering. This project combines vector-based document retrieval with open-source LLMs and includes an agentic workflow to understand retrieval decisions and generate answers step by step. Ideal for learning and experimenting with RAG systems.

---

## Features
- Retrieve relevant documents using semantic embeddings.
- Generate context-aware answers using free/open-source LLMs (e.g., GPT-J).
- Agentic workflow to decide when retrieval is necessary.
- Fully local setup, no OpenAI API required.
- Easy to extend with new documents or models.

---

## Installation
Make sure you have Python 3.10+ installed.  
Then install the required dependencies:

```bash
pip install langchain faiss-cpu transformers sentence-transformers
