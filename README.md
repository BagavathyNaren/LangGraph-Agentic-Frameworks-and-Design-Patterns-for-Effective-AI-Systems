Setup in Google Collab:

1. Change the runtime type to 2025.10 that uses Python 3.11.x version
2. Enable the OPENAI_API_KEY in Google Collab

Setup in Visual Studio Code (Local):

1. Create .env file and add the OPENAI_API_KEY to the file
2. Use .venv [3.11.13 Pyhton Version] or .conda [3.11.13 Pyhton Version]


# LangGraph-Agentic-Frameworks-and-Design-Patterns-for-Effective-AI-Systems
This is the LangGraph Agentic Frameworks and Design Patterns for Effective AI Systems Repo

1. Agentic AI Design Patterns
Agentic design patterns are reusable architectural strategies for coordinating multiple language-model agents into
structured workflows. Each agent has a defined role, scoped responsibility, and clear input/output contracts.
Fundamental Components
- Agent – Specialized LLM-driven unit
- Orchestrator – Central controller managing state and routing
- Worker – Single-responsibility execution unit
- Router – Intent-based dispatcher
- Evaluator – Output quality and correctness scorer
Pattern Description Use Cases
Orchestration Central controller manages agents Pipelines, workflows
Reflection Self-evaluation and refinement Quality improvement
Sequential Fixed agent ordering Multi-step reasoning
Routing Intent-based dispatch Multi-domain assistants
Parallel Concurrent execution Research, exploration



