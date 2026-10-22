# FastAPI Practice: Student API

My first FastAPI project: a small REST API that stores students in memory.

## Features

- Get a student by ID (path parameter with validation)
- Find a student by name
- Create, update and delete students using Pydantic models

## How to run

```bash
pip install fastapi uvicorn
uvicorn myapi:app --reload
```

Then open http://127.0.0.1:8000/docs to try the API.
