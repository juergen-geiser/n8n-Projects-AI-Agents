# n8n Projects – AI Agents

## Overview

This repository contains a collection of **AI Agent projects developed with n8n**, demonstrating how to build intelligent automation workflows using Large Language Models (LLMs), memory, external knowledge sources, and Retrieval-Augmented Generation (RAG).

The projects progress from simple AI Agents to more advanced workflows that integrate **OpenAI, Google Drive, document analysis, and knowledge-based question answering**.

## Project 1: Basic AI Agents with Memory

**Workflow files:**
- `Start-1.json`
- `Start-2.json`

**Description:**

Introduction to building simple AI Agents in n8n using OpenAI LLMs and conversational memory.

**Key features:**
- Integration with OpenAI language models
- Basic chatbot functionality
- Conversational memory for maintaining context
- Introduction to AI Agent workflows in n8n

## Project 2: AI Agents with External Knowledge

**Workflow files:**
- `start_3_1.json`
- `start_3_2.json`

**Description:**

Extend basic AI Agents by integrating external knowledge sources, such as PDF documents and CSV files.

**Key features:**
- Integration of external knowledge sources (PDF and CSV)
- AI-powered analysis of document content
- Conversational memory
- Knowledge-enhanced responses using OpenAI LLMs

## Project 3: AI Agent for Email Sentiment Analysis

**Workflow file:**
- `start_3_2_advanced_drive.json`

**Description:**

An AI Agent that analyzes customer emails retrieved from Google Drive, using additional information from a PDF knowledge base.

The analysis results are saved back to Google Drive.

**Key features:**
- Retrieval of customer emails from Google Drive
- Sentiment analysis of customer messages
- Integration of a PDF-based knowledge source
- Conversational memory
- Automated storage of analysis results in Google Drive

## Project 4: RAG-Based AI Agent for Customer Support

**Workflow files:**
- `Start_5_Rag.json`
- `Start_5_RAG_drive.json`

**Description:**

A more advanced AI Agent implementing **Retrieval-Augmented Generation (RAG)** to analyze customer emails and generate responses based on an external knowledge base.

The generated responses are saved to files and can be uploaded to Google Drive.

**Key features:**
- Retrieval-Augmented Generation (RAG)
- Integration of external knowledge bases
- Context-aware analysis of customer emails
- Generation of knowledge-grounded customer support responses
- Automated file creation and Google Drive integration

---

## Technologies Used

- **n8n** – Workflow automation and AI Agent orchestration
- **OpenAI LLMs** – Natural language understanding and generation
- **AI Agent Memory** – Maintaining conversational context
- **Google Drive** – Document retrieval and storage
- **PDF and CSV Files** – External knowledge sources
- **RAG** – Retrieval-Augmented Generation for knowledge-based responses

## Getting Started

1. Install or access an existing [n8n](https://n8n.io/) instance.
2. Download the desired workflow JSON file from this repository.
3. Open the n8n workflow editor.
4. Import the JSON file into n8n.
5. Configure the required credentials, such as OpenAI and Google Drive.
6. Adjust the workflow settings and input files as needed.
7. Execute the workflow and inspect the results.

**Note:** Some workflows require valid API credentials, access to Google Drive, and external knowledge files. These resources must be configured before execution.

## Learning Objectives

By working through these projects, you will learn how to:

1. Create and configure AI Agents in n8n.
2. Integrate OpenAI LLMs and conversational memory.
3. Process and analyze external documents.
4. Automate customer email sentiment analysis.
5. Build knowledge-based AI Agents using RAG.
6. Integrate Google Drive into AI-powered automation workflows.

---

## Project Progression

| Project | Topic | Main Focus |
|---|---|---|
| 1 | Basic AI Agents | OpenAI LLMs and memory |
| 2 | Knowledge-Enhanced Agents | PDF/CSV integration |
| 3 | Email Analysis Agent | Sentiment analysis and Google Drive |
| 4 | RAG Customer Support Agent | Knowledge-based response generation |

**From simple chatbots to intelligent, knowledge-driven AI automation with n8n.**
