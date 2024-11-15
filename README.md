# Retrieval-Augmented Generation (RAG) Pipeline

This repository contains a modular RAG pipeline that processes PDF documents, retrieves relevant information using embeddings, and generates answers using OpenAI's GPT.

## Features
- Extract text from PDF documents.
- Generate embeddings and store them in ChromaDB.
- Query the database and retrieve relevant chunks.
- Use GPT to generate natural language answers.

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- OpenAI API key (store in `.env` file)

### Installation
1. Clone this repository:
   ```bash
   git https://github.com/ManinderpalSingh08/ModularRAG-pipeline.git
   cd ModularRAG-pipeline
