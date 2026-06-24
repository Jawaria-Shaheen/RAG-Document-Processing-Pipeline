# RAG-Document-Processing-Pipeline
A Retrieval-Augmented Generation (RAG) document processing pipeline built with n8n, Google Gemini Embeddings, Pinecone, and Google Drive. The workflow automatically processes uploaded documents, generates embeddings, and stores them in a vector database for semantic search and AI-powered question answering.

# RAG Document Processing Pipeline

## Overview

This project implements the document ingestion and indexing layer of a Retrieval-Augmented Generation (RAG) system. It automatically monitors a Google Drive folder, processes newly uploaded documents, generates vector embeddings using Google Gemini Embeddings, and stores them in Pinecone Vector Database for efficient semantic retrieval.

The pipeline serves as the foundation for AI-powered document summarization, knowledge retrieval, and question-answering applications.

## Features

* Automatic document detection from Google Drive
* PDF and document processing
* Recursive text chunking
* Google Gemini Embeddings generation
* Pinecone vector database integration
* Metadata storage for document tracking
* Scalable RAG architecture
* No-code/low-code implementation using n8n

## Workflow

1. User uploads a document to Google Drive.
2. n8n detects the new file automatically.
3. The document is downloaded and processed.
4. Content is split into manageable text chunks.
5. Google Gemini generates vector embeddings.
6. Embeddings are stored in Pinecone.
7. Documents become searchable through semantic retrieval.

## Tech Stack

* n8n
* Google Drive API
* Google Gemini Embeddings
* Pinecone Vector Database
* RAG (Retrieval-Augmented Generation)

## Use Cases

* Document Question Answering
* Knowledge Base Systems
* AI Chatbots
* Enterprise Search
* Research Document Analysis
* Document Summarization

## Future Improvements

* Streamlit Frontend
* Interactive Chat Interface
* Multi-document Question Answering
* Automated Document Summaries
* Citation-based Responses
* Hybrid Search Support

## Architecture

Google Drive → n8n → Text Splitter → Gemini Embeddings → Pinecone Vector Store → RAG Application



