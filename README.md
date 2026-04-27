# RAG Chatbot (LangGraph + Groq API)

This project builds a Retrieval-Augmented Generation (RAG) chatbot using LangGraph, LangChain, and Groq API.
The chatbot retrieves relevant information from documents before generating answers.
---

## Features

* RAG-based chatbot
* Uses LangGraph workflow
* Integrates Groq API
* Context-aware responses
* Modular pipeline

---

## Tech Stack

* Python
* LangGraph
* LangChain
* Groq API
* Jupyter Notebook

---

## What is RAG

RAG (Retrieval-Augmented Generation) is a method where the model retrieves relevant data before generating a response.

Flow:

User Question → Retrieve Documents → Provide Context → Generate Answer

---

## How It Works

1. User asks a question
2. System retrieves relevant documents
3. Context is passed to the model
4. Model generates response
5. Final answer is returned

---

## Project Structure

* langgraph_groq_api.ipynb
* requirements.txt
* README.md

---

## Installation

Clone the repository:

git clone https://github.com/yourusername/rag-chatbot-langgraph.git

Go to the folder:

cd rag-chatbot-langgraph

Install dependencies:

pip install -r requirements.txt

---

## Usage

Run the notebook:

jupyter notebook

Open:

langgraph_groq_api.ipynb

---

## Use Cases

* Document Q&A
* AI assistants
* Knowledge-based chatbots
* Research tools
