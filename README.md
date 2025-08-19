# LangGraph Multi-Agent Example

This project demonstrates how to build both single-agent and multi-agent systems using [LangGraph](https://github.com/langchain-ai/langgraph), a framework for orchestrating stateful LLM workflows.


Install dependencies with:

```bash
pip install -r requirements.txt
```

## 📁 Project Structure

- `main.py`: Contains the full LangGraph implementation with routing and agents
- `requirements.txt`: Required packages
- `README.md`: This guide

## 🧠 How It Works

1. User inputs a query.
2. A router agent uses the LLM to decide whether the query is a math problem or general knowledge.
3. The appropriate agent handles the request.
4. LangGraph manages the state and transitions between nodes.
