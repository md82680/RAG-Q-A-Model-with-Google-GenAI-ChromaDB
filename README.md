# RAG Q&A Model with Google GenAI & ChromaDB

This repository demonstrates a RAG Q&A model leveraging Google GenAI for embeddings and ChromaDB for vector search. It indexes custom documents and retrieves relevant content to generate tailored natural language answers in an end-to-end pipeline.

## Overview

This project implements a Retrieval Augmented Generation (RAG) system that:
- Generates document embeddings using Google GenAI
- Uses ChromaDB for efficient vector-based document search
- Combines retrieval with natural language generation to answer questions based on custom documents

## Features

- **Document Indexing:** Convert custom documents into embeddings
- **Vector Search:** Retrieve relevant documents from ChromaDB
- **Tailored Generation:** Generate natural language answers using the Gemini API

## Setup & Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/md82680/RAG-QA-Model-with-Google-GenAI-ChromaDB.git
   cd RAG-QA-Model-with-Google-GenAI-ChromaDB

   ```

2. **Install Dependencies:**
   ```bash
   pip install -qU "google-genai==1.7.0" "chromadb==0.6.3"
   ```

3. **API Key Setup:**
   - Store your Google API key in your Kaggle secret (named GOOGLE_API_KEY) or as an environment variable

## Usage

Run the provided Jupyter Notebook to:
- Generate embeddings for your documents
- Create and populate the ChromaDB collection
- Execute queries and generate responses using the Gemini API

## Customization

You can modify the embedded documents, tweak the model parameters in the GeminiEmbeddingFunction, or experiment with different retrieval settings to tailor the pipeline to your needs.

## Project Structure

- **Notebooks:** Contains the end-to-end pipeline demonstration
- **src/:** Source code including custom embedding functions and database interactions
- **README.md:** This file

## License

This project is licensed under the Apache License 2.0.

## Acknowledgements

Thanks to Google GenAI, ChromaDB, and the Kaggle community for their excellent tools and resources.
