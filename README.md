# Customer Support Case Agent

This repository contains a **Streamlit** application that integrates **Azure AI** and **Cosmos DB** to create a customer support agent. The application uses **Azure OpenAI**, **Semantic Kernel**, and **custom avatar video generation** to handle customer cases, extract insights, and deliver personalized AI-driven support.

## Features

### Customer Case Management:
- Extract details from customer transcripts using **Azure OpenAI**.
- Save and retrieve case details from **Azure Cosmos DB**.

### Custom Avatar Video Generation:
- Generate personalized avatar videos using **Azure Speech Services**.
- Store and retrieve prompts and videos via **Azure Blob Storage**.

### Agent-Based Framework:
- Implements **multi-agent collaboration** using Semantic Kernel agents to analyze, manage, and resolve customer issues.

### Interactive UI:
- Upload transcripts, view extracted details, and generate avatar videos.
- Seamlessly process and manage customer cases.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd customer-support-agent
