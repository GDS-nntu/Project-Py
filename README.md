# Study Tasks API

Small learning project with FastAPI. The idea is to keep simple study tasks in a
JSON file and practice basic REST endpoints.

## Run locally

```bash
python -m venv .venv
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Open `http://127.0.0.1:8000/docs` to try the API.

## API draft

- `GET /tasks` - show all tasks
- `POST /tasks` - create a task with a title
- `GET /tasks/{task_id}` - show one task
- `PATCH /tasks/{task_id}` - mark a task as done or not done
