# UIUC-ML-AI-project

A Retrieval-Augmented Generation (RAG) based document search and question-answering system built using modern LLM and vector database technologies. This project focuses on improving the reliability, grounding, and accuracy of AI-generated responses through document retrieval and multi-agent verification.

## Overview

This system processes domain-specific documents, converts them into vector embeddings, stores them in a FAISS vector database, and retrieves relevant information to answer user queries using Large Language Models (LLMs).

In addition, the project explores a multi-agent architecture where one agent generates responses while another agent evaluates whether the answer is supported by retrieved evidence.

## Features

- Document ingestion and preprocessing
- Text chunking pipeline
- HuggingFace embedding generation
- FAISS vector database integration
- Retrieval-Augmented Generation (RAG)
- Multi-agent response verification workflow
- Prompt engineering experiments
- Grounded response evaluation

## System Architecture

1. Load and preprocess documents
2. Split documents into chunks
3. Generate embeddings using HuggingFace models
4. Store embeddings in FAISS vector database
5. Retrieve relevant chunks based on user query
6. Generate responses using LLM
7. Verify response grounding using a secondary agent
