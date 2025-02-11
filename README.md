# Agentic RAG with LlamaIndex

![image](https://github.com/user-attachments/assets/e4af9798-a0e9-41cc-9a23-0cefa4f4b51a)

## Overview
This repository explores advanced **Retrieval-Augmented Generation (RAG)** techniques using **LlamaIndex**. We delve into agentic capabilities to enhance reasoning, tool usage, and multi-document inference. The project showcases various RAG implementations with agents that can reason over structured and unstructured data sources.

## Features Explored
1. **Router Query Engine** - Implements intelligent query routing across different data sources for optimized information retrieval.

![image](https://github.com/user-attachments/assets/424415ce-c111-4526-a961-16739ec0e4e2)
   
3. **Tool Calling** - Enables the agent to call external tools dynamically to augment reasoning and enhance responses.
4. **Agent Reasoning Loop** - Builds a self-improving reasoning loop using an agent that can infer from structured PDFs, such as `metagpt.pdf`.
 
![image](https://github.com/user-attachments/assets/67350682-8730-45df-b2d8-4b4712cfe33e)

5. **Multi-Document Agent** - Analyzes and synthesizes insights from **11 research papers** on RAG, fine-tuning, and related topics to derive meaningful conclusions.

## Data Sources
- **Metagpt.pdf**: Acts as a structured knowledge base for agent inference.
- **Research Papers**: A collection of 11 papers covering RAG, fine-tuning, and advanced retrieval mechanisms.

## Technologies Used
- **LlamaIndex**: Core library for RAG implementation.
- **LangChain**: Used for orchestration and agent reasoning.
- **OpenAI API / LLMs**: Powering agent-based inference.
- **Vector Databases** (FAISS, ChromaDB): Efficient document retrieval and embedding storage.


## Future Enhancements
- Integrating reinforcement learning for agent feedback loops.
- Expanding tool-calling capabilities with additional APIs.
- Enhancing reasoning with chain-of-thought prompting.


