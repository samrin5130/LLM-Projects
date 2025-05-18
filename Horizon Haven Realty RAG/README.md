# Horizon Haven Realty Q&A Agent

## Overview
This project is a **Question & Answer agent** built using **Retrieval-Augmented Generation (RAG)** for a fictional real estate company, **Horizon Haven Realty**. The agent is designed to answer user queries by retrieving relevant information from a curated knowledge base and then generating accurate, natural language responses.

By combining **Chroma** as the vector store, **LangChain** for retrieval orchestration, and the **Qwen3:4B model** via **Ollama** for response generation, the agent can deliver informative answers based on the company's knowledge base.

This entire workflow has been implemented inside a **Jupyter Notebook**, allowing easy exploration, visualization, and interaction.

---

## Features
- Converts a custom knowledge base into vector embeddings using **sentence-transformers/all-MiniLM-L6-v2**.
- Visualizes document embeddings in **2D and 3D space** for better understanding.
- Implements a **RAG pipeline** using **LangChain** and **ChromaDB**.
- Provides an interactive **chat function** that lets users ask questions continuously until they type "exit".

---

## How It Works

1. **Embedding Creation**  
   We create vector embeddings for each chunk of the knowledge base using the **all-MiniLM-L6-v2** model from Hugging Face.

2. **Vector Store Setup**  
   The embeddings are stored in a **Chroma** vector store for efficient retrieval.

3. **Visualization**  
   We visualize the documents and their embedding vectors by reducing them to **2D and 3D**, helping us see how the knowledge base is structured in vector space.

4. **Chat Interface**  
   A simple chat function allows users to interact with the agent, where queries are processed using the **RAG pipeline**, and responses are generated using **Qwen3:4B**.

---

## Prerequisites

Before running the notebook, ensure the following are set up:

- **Python 3.7+**
- **Ollama** installed from https://ollama.com/
- **Qwen3:4B model** downloaded and available in your local Ollama setup
