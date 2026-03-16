# Customer Support AI Chatbot

This project implements a customer support chatbot using:

- LLM-style response generation
- RAG (Retrieval Augmented Generation)
- FAISS vector database
- SQL database for structured order data

## Features

- Order tracking
- Payment status retrieval
- Refund status checking
- Policy information retrieval
- Hybrid SQL + RAG retrieval
- Interactive chatbot UI using Gradio

## Tech Stack

Python  
FAISS  
SentenceTransformers  
SQLite  
Gradio  
Pandas  

## Example Queries

Where is order 101?  
What is the refund status for order 102?  
Show Rahul orders  
What is the return policy?

## Architecture

User Query  
↓  
Intent Detection  
↓  
SQL Database + RAG Retrieval  
↓  
Customer Friendly Response
