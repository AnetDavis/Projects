# RAG Chatbot

## Objective

This project implements a Retrieval-Augmented Generation (RAG) chatbot that answers user questions using information retrieved from a document. The chatbot combines semantic search with a Large Language Model to generate accurate, context-aware responses based only on the relevant document content.

## Dataset

- **Document:** Amazon Quarterly Report (10-Q)
- **Source:** SEC Filing
- **Problem Type:** Retrieval-Augmented Question Answering (RAG)

## Project Workflow

### 1. Document Processing
- Load the quarterly report.
- Extract and clean the document text.
- Split the document into smaller chunks.

### 2. Embedding Generation
- Generate vector embeddings using Sentence Transformers.
- Store embeddings in a FAISS vector database.

### 3. Retrieval
- Convert the user's query into an embedding.
- Retrieve the most relevant document chunks using FAISS similarity search.

### 4. Response Generation
- Pass the retrieved context to the Gemini model.
- Generate a context-aware answer with supporting information.

### 5. Web Application
- Build the backend using FastAPI.
- Create an interactive chat interface for users.
- Return responses based on retrieved document content.

## Technologies Used

- Python
- FastAPI
- Sentence Transformers
- FAISS
- Google Gemini API
- HTML
- CSS
- JavaScript

## Results

The chatbot successfully retrieves relevant information from the document and generates accurate responses using Retrieval-Augmented Generation. The combination of semantic search and large language models improves answer quality while reducing hallucinations.

## Conclusion

This project demonstrates how Retrieval-Augmented Generation can be used to build intelligent document-based chatbots. By integrating vector search with a language model, the system provides reliable and context-aware answers from the uploaded document.

## Author

**Name:** Anet Davis

**Registration Number:** 23BHI10146

**Application Number:** IN26011852

**Batch Number:** 1A

**Email ID:** anet.23bhi10146@vitbhopal.ac.in
