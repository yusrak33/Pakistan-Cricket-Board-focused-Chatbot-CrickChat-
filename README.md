# Pakistan-Cricket-Board-focused-Chatbot-CrickChat-
AI chatbot for PCB cricket player statistics
CrickChat is an AI-powered chatbot that answers questions about Pakistani cricket players using a structured dataset of 70+ entries. It provides player stats like ODI, Test, and T20 runs, international records, and personal details.

The chatbot is built using:

Sentence Embeddings: sentence-transformers/all-MiniLM-L6-v2

Model: google flan t5 (via Hugging Face)

Vector Store: FAISS for fast similarity search

Framework: LangChain for managing the conversational pipeline

Interface: Supports both text and voice input modes

It’s designed to give human-like, grounded responses from the dataset with no hallucinations.
