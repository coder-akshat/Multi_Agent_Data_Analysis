![image](https://github.com/user-attachments/assets/e124c4a7-18ea-49f2-8726-f16d1207e63f)

# Multi-Agent Data Analysis System
![bfb52a27-471e-4baf-aa8d-40f7313baec4](https://github.com/user-attachments/assets/034f958e-a947-4164-9e81-f8c44b472925)


This Agentic system is designed to handle complex data analysis tasks by breaking them down into smaller subtasks and delegating them to specialized agents. The system uses a multi-agent architecture to improve performance and scalability.

## System Components

- **Agent Orchestrator**: The main controller that coordinates the work of the agents.
- **Data Analyst Agent**: Handles data analysis tasks.
- **SQL Data Analyst Agent**: Specialized in SQL-based data analysis.
- **Visualization Server**: Manages the visualization of data analysis results.

## System Design Diagram:
![screencapture-mermaid-live-view-2025-04-15-01_00_08](https://github.com/user-attachments/assets/2e56f0dc-1865-4dc5-a292-a6ff6fe317f6)


## Setup

1. Install dependencies:
```bash
uv venv
uv sync
```

2. Set up environment variables:
```bash
cp .env.example .env # OPENAI_API_KEY
```

3. Run the application:
```bash
python main.py
```

## Usage

1. Access the API at `http://localhost:8080`.
2. Use the endpoints provided by the API to interact with the system.

## Testing

1. Run tests:
```bash
python -m pytest
```

2. Run coverage report:
```bash
python -m pytest --cov=app
```

## License

MIT License

## Acknowledgments

- [FastAPI](https://fastapi.tiangolo.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Plotly](https://plotly.com/)
- [OpenAI](https://openai.com/)
- [IDX](https://idx.dev/)
- [Pydantic_AI](https://ai.pydantic.dev/)
- [LangGraph](https://github.com/langchain-ai/langgraph)


