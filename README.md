# LangChain: Hands-On Learning 🚀

## Overview

This repository documents my hands-on learning journey with **LangChain**, a framework for building applications powered by Large Language Models (LLMs).

I explored the core components of LangChain and practiced building LLM-powered workflows using Groq, prompt templates, retrieval-augmented generation (RAG), tools, structured outputs, memory, and agents.

The examples were developed using **Python and Google Colab**, with Groq as the LLM provider.

## Topics Covered

### 1. LLM Integration

* Understanding Large Language Models and chat models.
* Integrating Groq models using `ChatGroq`.
* Invoking models using `invoke()`.
* Understanding model responses and message types.
* Exploring temperature and model configuration.

### 2. Prompt Engineering

* `PromptTemplate`
* `ChatPromptTemplate`
* System and human messages.
* Dynamic prompt variables.
* Formatting prompts for different use cases.

### 3. Chains and LCEL

* Understanding chains and their execution flow.
* LangChain Expression Language (LCEL).
* Chaining components using the `|` operator.
* Using `RunnablePassthrough` and `RunnableLambda`.
* Exploring `invoke()`, `batch()`, and `stream()`.
* Parsing model responses using `StrOutputParser`.

### 4. Retrieval-Augmented Generation (RAG)

* Understanding the RAG architecture.
* Creating and working with `Document` objects.
* Document chunking and retrieval concepts.
* Generating embeddings using Hugging Face.
* Creating a FAISS vector store.
* Performing similarity search using retrievers.
* Combining retrieved context with LLM responses.
* Building a basic RAG pipeline for answering questions from documents.

### 5. Tools and Tool Calling

* Creating custom tools using the `@tool` decorator.
* Defining tool descriptions and arguments.
* Invoking tools with structured inputs.
* Understanding `bind_tools()` and model-generated tool calls.
* Exploring how agents select and use tools.

### 6. Structured Output

* Defining schemas using Pydantic.
* Using `BaseModel` and `Field`.
* Generating structured responses using `with_structured_output()`.
* Validating model outputs for downstream application logic.

### 7. Conversation Memory

* Understanding conversation history and session-based memory.
* Using `InMemoryChatMessageHistory`.
* Working with `MessagesPlaceholder`.
* Using `RunnableWithMessageHistory`.
* Managing conversation history with session IDs.
* Understanding the difference between temporary in-memory history and persistent storage.

### 8. AI Agents

* Understanding agents and their execution flow.
* Creating agents using `create_agent()`.
* Connecting chat models with custom tools.
* Exploring tool selection and tool execution.
* Understanding the difference between predefined chains and dynamic agent workflows.

## Tech Stack

* **Language:** Python
* **Framework:** LangChain
* **LLM Provider:** Groq
* **Model Integration:** `langchain-groq`
* **Embeddings:** Hugging Face
* **Vector Search:** FAISS
* **Data Validation:** Pydantic
* **Environment:** Google Colab

## Key Learnings

Through these hands-on exercises, I learned how to:

* Integrate LLMs into Python applications.
* Build reusable prompt and chain pipelines.
* Implement semantic document retrieval.
* Develop basic RAG-based question-answering systems.
* Create custom tools and connect them with AI models.
* Generate structured model outputs.
* Manage conversational history across sessions.
* Understand the fundamentals of tool-using AI agents.

## Learning Resources

* [Official LangChain Documentation](https://docs.langchain.com/oss/python/learn)
* [LangChain RAG Tutorials](https://docs.langchain.com/oss/python/langchain/rag)
* [Groq Console](https://console.groq.com/)

## Next Steps

My next learning goal is to explore **LangGraph** for stateful AI workflows, conditional routing, checkpointing, human-in-the-loop systems, and multi-agent orchestration.

---

*This repository is part of my hands-on learning journey in Generative AI and Agentic AI development.*
