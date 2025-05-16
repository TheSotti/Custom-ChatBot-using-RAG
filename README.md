# 📚 Custom Question-Answering Chatbot using RAG 

## 🧠  Project Overview
This project implements a custom question-answering chatbot that uses Retrieval-Augmented Generation (RAG) to deliver accurate and context-aware responses. The chatbot is tailored to answer questions based on personal information retrieved from my CV.

By combining retrieval-based techniques with the generative capabilities of large language models, the chatbot can provide detailed and relevant answers grounded in the source data.

## Features
🔍 Retrieval-Augmented Generation (RAG): Enhances answer accuracy by retrieving supporting information.

📄 Contextual Retrieval: Fetches relevant passages from stored CV data using semantic search.

🧮 Cosine Similarity: Ranks candidate contexts based on vector similarity.

🤖 Response Generation: Uses a fine-tuned language model to generate natural answers from retrieved context.

🧠 Custom Knowledge Base: Built specifically from personal CV information.

## ⚙️ How It Works
### - Data Processing

Parses and cleans the CV text to extract relevant sections.

Structures the data for efficient retrieval.

### - Embedding Generation

Converts processed CV text into dense vector embeddings using a pre-trained embedding model.

### - Retrieval Mechanism

On user query, computes embeddings and uses cosine similarity to find the most relevant context from the knowledge base.

### - Response Generation

Feeds the top-matched context and the user query into a language model (optionally fine-tuned).

Generates an accurate and context-aware answer.
