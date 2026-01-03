# 📈 Stock Analysis System (Agent-Based)

This project implements an **agent-based stock analysis system** that automates financial analysis using multiple specialized AI agents.

The system follows a task-driven architecture where agents collaborate to analyze stock-related information, perform calculations, and retrieve financial data using modular tools.

## Project Overview

- Agent-based architecture for stock analysis
- Task and agent configuration using YAML files
- Modular tools for calculations and SEC data access
- Central orchestration using a crew-based workflow

## Project Structure

```bash
stock_analysis/
├── config/
│ ├── agents.yaml
│ └── tasks.yaml
├── tools/
│ ├── calculator_tool.py
│ └── sec_tools.py
├── crew.py
├── main.py
├── env.example
├── pyproject.toml
└── README.md
```


## Environment Configuration

The required environment variables are listed in `env.example`.  
Copy this file and update values as needed before running the project.

## Notes

This project demonstrates **agentic AI workflows** applied to stock analysis and is intended for learning and experimentation.
