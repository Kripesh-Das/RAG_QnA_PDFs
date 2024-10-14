# RAG Document Q&A with Groq and Llama3
## This Streamlit application allows users to query research papers using a Retrieval-Augmented Generation (RAG) approach with Groq and Llama3 models.

## Features:
### -Document Embedding: Ingests and processes research papers to create vector embeddings.
### -Query Interface: Users can input queries to retrieve answers based on the context of the research papers.
### -Document Similarity Search: Displays similar documents based on the query.
## Setup:
### -Environment Variables: Ensure OPENAI_API_KEY and GROQ_API_KEY are set in your environment.
### -Install Dependencies: Use pip to install required packages.
### -Run the App: Execute the Streamlit app using streamlit run app.py.
## Key Components:
### -Vector Embedding Creation: Loads and splits documents, then creates vector embeddings using FAISS.
### -Query Handling: Uses a retrieval chain to process user queries and return relevant answers and documents.


##  Create a .env file to create the entire LANGCHAIN ecosystem.
      LANGCHAIN_TRACING_V2=true
      LANGCHAIN_ENDPOINT=
      LANGCHAIN_API_KEY = 
      LANGCHAIN_PROJECT=
      OPEN_API_KEY=
      GROQ_API_KEY=

##  Use Python 3.11 virtual environment to complete the project.
## Screenshots of the actual working model on streamlit are provided in "project_demonstration" folder

