# RAG-Based Chatbot for Financial Reports

## Overview
This project addresses the challenge of navigating complex financial reports. We developed a chatbot powered by Retrieval-Augmented Generation (RAG) to provide real-time insights from financial documents.

### Key Features
- Combines document retrieval with AI-generated responses.
- Processes financial documents like annual reports for user-friendly insights.
- Interactive interface for real-time queries.

## Technical Highlights
- **Document Processing**: PyPDFLoader to parse and split PDFs.
- **Semantic Search**: OpenAI embeddings with FAISS for similarity search.
- **Language Model**: OpenAI’s GPT for generating accurate answers.
- **User Interface**: Built with Streamlit for real-time interactions.
- **Arabic Data Handling**: Supports Arabic text processing using language-specific embeddings and chunking.

## Challenges and Solutions
- **Complex Data**: Addressed with language detection and chunking.
- **Time Constraints**: Prioritized essential features and used pre-trained models.

