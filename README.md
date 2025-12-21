# ASSITA

An **AI-driven customer support system** built using **LangChain**, **LangGraph**, **Groq LLMs**, and **Gradio**.  
The application intelligently analyzes customer queries, detects **sentiment**, classifies the **query category**, and routes the request to the appropriate support handler or escalates it when required.

---

## 🚀 Features

- 🔍 **Automatic Query Categorization**
  - Technical
  - Billing
  - General

- 😊 **Sentiment Analysis**
  - Positive
  - Neutral
  - Negative

- 🔀 **Dynamic Workflow Routing**
  - Built using **LangGraph**
  - Negative sentiment queries are escalated to a human agent

- 🤖 **LLM-Powered Responses**
  - Powered by **Groq’s LLaMA 3.3 (70B)** model

- 🧩 **Visual Workflow Graph**
  - Mermaid-based workflow visualization

- 🌐 **Interactive Web Interface**
  - Simple and clean UI built with **Gradio**

---

## 🏗️ Architecture Overview

The system follows a structured workflow:

1. **Categorize Query**
2. **Analyze Sentiment**
3. **Conditional Routing**
   - Technical → Technical Handler
   - Billing → Billing Handler
   - General → General Handler
   - Negative Sentiment → Escalation
4. **Generate Final Response**

---

## 🛠️ Tech Stack

- Python
- LangChain
- LangGraph
- Groq LLM (LLaMA 3.3 70B)
- Gradio
- Mermaid (Workflow Visualization)

---

## 📦 Installation

```bash
pip install langchain langchain_core langchain_groq langchain_community langgraph gradio
