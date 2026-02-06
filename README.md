# FastAPI Production Starter

A small, opinionated FastAPI starter for building maintainable APIs with sane defaults.

This is not a demo project.  
This is a foundation you can build on without rewriting everything later.

---
Purchase: https://zerolevel.gumroad.com/l/oxhfsc?layout=profile


---

## Who This Is For

- Freelancers shipping APIs for clients
- Indie developers building internal tools or MVPs
- Small teams that want structure without framework lock-in

If you want a giant boilerplate with every feature imaginable, this is not it.

---

## What You Get

- Clean project structure
- Environment-based configuration
- Centralized logging
- Centralized error handling
- SQLAlchemy 2.0 setup
- Service layer pattern
- Example CRUD resource
- One working test

---

## What This Intentionally Does NOT Include

- Authentication
- Background job queues
- WebSockets
- Database migrations
- Cloud-specific configuration

Those choices are left to you, on purpose.

---

## Project Structure

```text
app/
  api/
  core/
  db/
  models/
  schemas/
  services/
tests/

```
## Run Locally
pip install -r requirements.txt
uvicorn app.main:app --reload

## Open
http://127.0.0.1:8000/docs

## Test
pytest

