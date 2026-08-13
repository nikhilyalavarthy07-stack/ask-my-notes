# Backend (FastAPI)

A minimal FastAPI backend for the frontend in `frontend/`.

Run locally (Windows):

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

Endpoint:

- `POST /ask` — accepts JSON `{ "question": "..." }` and returns `{ "answer": "..." }`.
