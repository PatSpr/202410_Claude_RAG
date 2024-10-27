# 🚀 Retrieval-Augmented Generation (RAG) Setup Guide

## 🌟 Highlights

- **Quick and Easy Setup**: Get started with RAG without complicated registrations or lengthy searches.
- **Integrated Environment**: Use VSCode and Jupyter Notebooks for a seamless coding experience.
- **Flexible Knowledge Base**: Support for various file formats (.txt, .csv, .docx, .pdf) or web content extraction.
- **State-of-the-Art Models**: Leverage Claude 3 haiku and HuggingFace’s embedding models for efficient text processing.
- **Advanced Querying**: Utilize Llama Index for loading documents and executing intelligent queries.
- **Scalable and Expandable**: Easily adapt your RAG solution from experimentation to production.

---

## ℹ️ Overview

The **Retrieval-Augmented Generation (RAG)** project is designed to streamline the integration of large language models (LLMs) with external knowledge sources. By employing a flexible knowledge base and powerful embedding techniques, this setup empowers users to generate coherent and contextually relevant responses to queries.

Whether you're looking to enhance your understanding of RAG or implement it in a production environment, this guide offers clear steps and practical advice. It’s perfect for anyone, from students to seasoned developers, who want to explore the capabilities of LLMs and their application in various domains.

---

## 🛠️ Getting Started

### 1. Working Environment

- **VSCode**: Set up a project with a virtual environment.
- **Jupyter Notebooks**: Install the extension for an enhanced coding experience.#
- **Anthrophic**: Setup an Account and charge up with 5 euros for API usage.

### 2. Knowledge Base

#### 2.1 Simple Method

- Place your `.csv`, `.txt`, `.docx`, or `.pdf` files in the `cleaned_data` folder.

#### 2.2 Web-Based Extraction

- Extract data from web pages, saving and cleaning it for further use. 
- Place your URLs into the "KnowledgeURL.csv" file, check for the websites privacy / data extraction and usage rules and act accordingly to it

### 3. LLM & Embedding

#### 3.1 Dependency Setup

Run these commands:

```bash
!python -m pip install llama-index
!python -m pip install llama-index-llms-anthropic
!python -m pip install llama-index-embeddings-huggingface 
!python -m pip install python-dotenv
!python -m ensurepip 
!pip -m pip install beautifulsoup4
!pip -m pip install numpy 
!pip -m pip install pandas
!pip -m pip install requests 
```

## 3.2 Loading Environment Variables

Load your environment variables securely using Python .env file.

## 4. Llama Index, Document Loading & Querying

Build your index and execute queries using Llama Index for intelligent responses.

## 5. Expanding Your Knowledge

Consider adding structured data and advanced embedding models to your knowledge base.

## 6. Considerations for Production

Evaluate performance, scalability, and security as you move to production.