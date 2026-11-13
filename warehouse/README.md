# Warehouse backend

The backend source is in `backend/`:

- `main.py` defines the FastAPI endpoints.
- `functions.py` contains database and authentication helpers.

Set `WAREHOUSE_SECRET_KEY` to a strong, private value before using token-based
authentication. Do not commit the secret or the local SQLite database.

PowerShell example:

```powershell
$env:WAREHOUSE_SECRET_KEY = "<set-a-strong-private-value>"
```
