# Debugging Using LangSmith

## Overview

This repository demonstrates how to use **LangSmith** for debugging, monitoring, and evaluating Large Language Model (LLM) applications built with LangGraph and LangChain.

LangSmith provides end-to-end observability by tracing every step of an AI workflow, including prompts, responses, tool calls, execution paths, latency, and errors. It enables developers to analyze agent behavior, identify bottlenecks, and improve the reliability and performance of AI applications.

This project showcases the integration of LangSmith into an AI agent workflow for real-time debugging and execution tracing.

---

## Features

- LangSmith integration for AI application monitoring
- End-to-end execution tracing
- Prompt and response inspection
- Tool call visualization
- Agent workflow debugging
- Performance monitoring
- Error tracking and analysis

---

## Project Structure

```
Debugging_LangSmith/
│
├── agent.py              # AI agent implementation
├── langgraph.json        # LangGraph configuration
├── .env                  # Environment variables
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

---

## Technologies Used

- Python
- LangSmith
- LangGraph
- LangChain
- Large Language Models (LLMs)
- Prompt Engineering
- JSON

---

## Workflow

1. Configure LangSmith credentials.
2. Initialize the LangGraph agent.
3. Execute AI workflows.
4. Capture prompts, responses, and tool executions.
5. Analyze execution traces in the LangSmith dashboard.
6. Identify errors, optimize prompts, and improve workflow performance.

---

## Installation

Clone the repository

```bash
git clone https://github.com/ThodupunooriSaiManish/Debugging_Langsmith.git
```

Navigate to the project directory

```bash
cd Debugging_Langsmith
```

Install the required packages

```bash
pip install -r requirements.txt
```

---

## Environment Setup

Create a `.env` file and configure the required API keys.

Example:

```env
LANGCHAIN_API_KEY=your_api_key
LANGCHAIN_PROJECT=Debugging_LangSmith
LANGCHAIN_TRACING_V2=true
```

---

## Running the Project

Execute

```bash
python agent.py
```

The application will start the AI agent while recording execution traces in LangSmith.

---

## Learning Outcomes

Through this project, I learned:

- AI workflow debugging using LangSmith
- End-to-end execution tracing
- Prompt inspection and optimization
- Agent observability
- Performance monitoring
- Error analysis for LLM applications

---

## Future Enhancements

- Multi-agent debugging support
- Performance benchmarking dashboard
- Automated evaluation metrics
- Integration with external tools using MCP
- Advanced prompt optimization workflows
- Cloud deployment with Docker

---

## Author

**Thodupunoori Sai Manish**
