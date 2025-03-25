# 🤖 Agentic RAG with LlamaIndex

A hands-on tutorial series on building advanced Retrieval-Augmented Generation (RAG) systems using LlamaIndex, with a focus on agentic capabilities and multi-document reasoning.

## 📚 Description

This repository contains a progressive series of Jupyter notebooks that demonstrate how to build increasingly sophisticated RAG systems using LlamaIndex. The course starts with basic router query engines and progresses to advanced multi-document agents with dynamic tool selection.

Each lesson builds upon the previous one, introducing new concepts and techniques for working with document-based knowledge and LLM agents.

## 🔍 Features

- **Router Query Engines**: Learn how to route queries to the most appropriate query engine based on the query content
- **Tool Calling**: Implement function-calling capabilities to enable LLMs to use tools for retrieving information
- **Agent Reasoning Loop**: Build an agent that can reason over documents and maintain a conversation
- **Multi-Document Agent**: Create a sophisticated agent that can work with multiple documents and dynamically select the most relevant tools

## 🛠️ Prerequisites

- Python 3.9+
- OpenAI API key (stored in a `.env` file)
- Required packages (see `requirements.txt`)

## 🚀 Setup Guide

1. Clone this repository
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
4. Run the Jupyter notebooks in order:
   - L1_Router_Engine.ipynb
   - L2_Tool_Calling.ipynb
   - L3_Building_an_Agent_Reasoning_Loop.ipynb
   - L4_Building_a_Multi-Document_Agent.ipynb

## 📖 Lesson Overview

### Lesson 1: Router Engine
Learn how to create a router query engine that can direct queries to either a summary index or a vector index based on the query content.

### Lesson 2: Tool Calling
Explore how to define and use tools with LLMs, including simple function tools and auto-retrieval tools for querying documents.

### Lesson 3: Building an Agent Reasoning Loop
Build an agent that can reason over documents, maintain a conversation, and provide detailed responses with source attribution.

### Lesson 4: Building a Multi-Document Agent
Create a sophisticated agent that can work with multiple documents, dynamically select the most relevant tools, and compare information across different sources.

## 🔗 Resources

- [LlamaIndex Documentation](https://docs.llamaindex.ai/)
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)

## 📝 License

This project is open source and available for educational purposes.
