```markdown
# Agentic AI Experiments
Exploration of Agentic AI workflows, MCP (Model Context Protocol), and LLM orchestration.

## Features
- Custom tool definitions for data retrieval.
- Multi-agent orchestration patterns.

## Sample Tool Definition
```python
# tools.py
def get_data_schema(table_name):
    """Retrieves the schema for a given Delta table."""
    return spark.table(table_name).schema.json()
