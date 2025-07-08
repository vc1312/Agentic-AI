# Agentic-AI

LangChain is a framework for developing applications powered by large language models (LLMs).

## Useful Commands -
Setup Virtual Environment
- create virtual env : conda create --name myenv python=3.10
- activate venv : conda activate venv
- deactivate venv: conda deactivate

LangChain is a framework to help you build applications that use large language models (LLMs) like ChatGPT — but in a smarter and more powerful way.

Think of it like a middleware for LLMs — it helps you connect models with tools, memory, documents, databases, and logic to build real apps.


# Why LangChain?
ChatGPT is great for answering prompts — but it:

- Doesn’t remember past chats in code
- Can’t access your data
- Can’t make decisions or call APIs

LangChain lets you build applications that solve all this:

- Add memory
- Use your documents or databases
- Call APIs
- Perform multi-step reasoning
- Build agents that act intelligently

Let’s break this into modules, like Lego blocks:

| Module         | What It Does                 | Example                                             |
| -------------- | ---------------------------- | --------------------------------------------------- |
| **LLM**        | Talks to models like ChatGPT | Ask "Summarize this doc"                            |
| **Prompt**     | How you talk to the model    | “Given a document, summarize it in 3 bullet points” |
| **Chains**     | Sequences of steps           | First read file → then summarize → then email       |
| **Memory**     | Makes the model remember     | Chatbot remembers your name or past questions       |
| **Tools**      | Connects to real-world tools | Search Google, query a database, call APIs          |
| **Agents**     | Smart decision-makers        | Decide “what to do next” based on goal              |
| **Retrievers** | Find info from documents     | Pull relevant PDF chunks for LLM                    |
| **Callbacks**  | Observe or debug             | Log what's happening behind the scenes              |


# When Should You Use LangChain?
Use LangChain if you're:

- Building a custom LLM-powered app
- Want your LLM to use tools/APIs
- Need context from external data (PDFs, DBs)
- Want to build multi-step logic (e.g., RAG, agents, workflows)