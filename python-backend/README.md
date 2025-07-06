# Backend Service - Document Analyzer API

This is the FastAPI backend for the MCP AI Web App. It handles document uploads, processing, and answering queries using a Large Language Model.

## Setup and Installation

This project uses `uv` for package management.

1.  **Create the virtual environment:**
    ```bash
    uv venv
    ```
2.  **Install dependencies:**
    ```bash
    uv pip install -r requirements.txt
    ```

## Running the Application

To run the development server with hot-reloading:

```bash
uv run uvicorn src.app.main:app --reload
```

The API will be available at `http://127.0.0.1:8000`.