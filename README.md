# AgentsVille Trip Planner

A Udacity project demonstrating advanced LLM reasoning techniques through an AI-powered travel planning system.

## Overview

This project implements an AI agent that plans a trip to the fictional city of **AgentsVille**. It showcases:

- **Role-Based Prompting** — specialized travel planner agent
- **Chain-of-Thought Reasoning** — step-by-step itinerary planning
- **ReAct Prompting** — Thought → Action → Observation cycles
- **Feedback Loops** — self-evaluation and iterative refinement

## Project Structure

```
.
├── project_starter.ipynb   # Main notebook with project steps
├── project_lib.py          # Utility classes and functions (ChatAgent, etc.)
├── .env                    # API keys (not committed)
├── .gitignore
└── README.md
```

## Setup

1. **Create and activate the virtual environment:**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # Windows
   ```

2. **Install dependencies:**
   ```bash
   pip install json-repair==0.47.1 numexpr==2.11.0 openai==1.74.0 pandas==2.3.0 pydantic==2.11.7 python-dotenv==1.1.0 ipykernel
   ```

3. **Configure your API key** in the notebook or create a `.env` file:
   ```
   OPENAI_API_KEY=your_key_here
   ```

4. **Select the kernel** in VS Code: `AgentsVille (.venv, Python 3.13)`

## Requirements

- Python 3.13+
- OpenAI API key (or Vocareum API endpoint for Udacity workspace)
