# Credit Card Approver

This application is for the Taktile Take Home Assessment. We simulate a client from a digital-only bank on the frontend, that uses our `approve_credit_card_application(...)` api defined on the backend/ (which is the Taktile service).

## Run locally

```bash
# terminal 1
cd backend && uv run uvicorn backend.main:app --reload --port 8000

# terminal 2
cd frontend && npm install && npm run dev
```

Open http://localhost:5173.
