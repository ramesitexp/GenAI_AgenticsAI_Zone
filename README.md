# LangChain Agents

This project contains LangChain-based AI agents for educational purposes.

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file from `.env.example`:
```bash
cp .env.example .env
```

3. Add your OpenAI API key to `.env`:
```
OPENAI_API_KEY=sk-proj-your-key-here
```

## Notebooks

- **notebooks/langchainagents.ipynb** - Course scheduling and recommendation agent
- **notebooks/db_agent.ipynb** - Database agent with Neon PostgreSQL integration

## Running

Open the notebooks in Jupyter and run the cells. The agent will use tools to answer queries.
