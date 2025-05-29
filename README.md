# Semantic Chunking and Finetuned LLM Adaptation Strategy for RAG-Chatbots
This project aims to enhance medical information retrieval for remote patients in the era of Healthcare 5.0. It leverages Language Model (LLM) finetuning and Semantic Chunking within a Retrieval-Augmented Generation (RAG) based Chatbot framework to provide personalized information from various medical documents, addressing the challenge of LLM hallucinations.

## Features

1. **Localized Setup**: The entire setup, including the LLM and the database, runs locally on the CPU.
2. **Qdrant Vector Database**: The project utilizes a Qdrant Docker database for storing chunks of medical documents.
3. **Semantic Chunking**: Semantic chunking techniques are employed to derive chunks from the provided medical documents.
4. **Finetuned LLM**: The project uses the BioMistral-7B model, a MEDICAL DOMAIN FINE-tuned model, for enhanced understanding and learning of medical information.
5. **Word Embeddings**: Pubmed-bert is used for obtaining dense embeddings of words.
