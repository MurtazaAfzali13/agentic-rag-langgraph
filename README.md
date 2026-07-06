# Agentic RAG with LangGraph

An educational implementation of an Agentic Retrieval-Augmented Generation (RAG) workflow using LangGraph, LangChain, OpenAI, ChromaDB, and Tavily Search.

This repository documents my learning process while building an adaptive RAG pipeline with graph-based orchestration. The project demonstrates how retrieval, document grading, web search, routing, and response generation can be combined into a production-oriented workflow.

## Features

* Graph-based RAG workflow with LangGraph
* Local document retrieval using ChromaDB
* Document relevance grading
* Adaptive routing between local knowledge and web search
* Web search integration with Tavily
* Answer generation with OpenAI models
* Self-evaluation and iterative improvement
* Modular node-based architecture

## Project Structure

```
graph/
ingestion/
prompts/
tests/
main.py
requirements.txt
```

## Environment Variables

Create a `.env` file with the following variables:

```env
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
LANGCHAIN_API_KEY=your_langsmith_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=agentic-rag
```

## Installation

```bash
git clone https://github.com/<your-username>/agentic-rag.git
cd agentic-rag

pip install -r requirements.txt
```

or

```bash
poetry install
```

## Run

```bash
python main.py
```

or

```bash
poetry run python main.py
```

## Learning Goals

This project covers:

* LangGraph fundamentals
* Agentic RAG architecture
* Vector databases
* Retrieval pipelines
* State management
* Conditional graph execution
* Web search integration
* Hallucination detection
* Adaptive retrieval strategies

## Acknowledgements

This repository was created for educational purposes while studying Agentic RAG with LangGraph.

The implementation is inspired by the original LangGraph course and examples created by Marco and the LangChain community. The code has been adapted and modified as part of my personal learning journey.
