## Hi 👋, I'm Michał (Glover012)
**Passionate about programming, focusing on backend Python technologies.**

### 🛠️ Technologies
- **Language**: Python
- **Web / API**: FastAPI, Pydantic, REST, OpenAPI / Swagger UI, uvicorn
- **Databases**: PostgreSQL, SQL, PL/pgSQL, SQLAlchemy ORM, Alembic
- **Security**: JWT, OAuth2, Argon2, role-based access control (RBAC)
- **Containerization**: Docker, Docker Compose
- **CI/CD**: GitHub Actions
- **Testing**: pytest, pytest-qt, pytest-mock, pytest-cov, Postman CLI
- **Test types**: unit, manual, GUI, API (end-to-end, negative, access control)
- **Static analysis**: mypy, ruff
- **GUI**: PySide6
- **Tools**: Git, GitLab, Bash, pip-tools
- **Systems**: Linux (Ubuntu), WSL2

### 🗂️ My projects
| Project | Description | Stack |
|---|---|---|
| 1️⃣ **[event-booking-api](https://github.com/Glover012/event-booking-api)** | REST API for publishing and booking events. **25 endpoints**, role-based access control (RBAC), JWT + Argon2, event lifecycle as an explicit transition map, row locking that prevents overselling, one uniform response envelope on every answer. Ships a **built-in CLI** that starts and manages the whole environment: secrets, volumes, migrations and seed data. CI with tests, lint and type checks. | `Python` `FastAPI` `Pydantic` `uvicorn` `SQLAlchemy` `PostgreSQL` `psycopg` `Alembic` `Docker` `Docker Compose` `GitHub Actions` `mypy` `ruff` |
| 2️⃣ **[quiz-app](https://github.com/Glover012/quiz-app)** | Desktop quiz app on the OpenTDB API. Background question loading on a managed `QThread`, custom exception hierarchy, user-facing error states, per-session logging. **~93% test coverage** with mocked HTTP responses, CI across Python 3.11–3.14. | `Python` `PySide6` `requests` `pytest` `pytest-qt` `pytest-mock` `pytest-cov` `GitHub Actions` |
| 3️⃣ **[mini-project-collection](https://github.com/Glover012/mini-project-collection)** | Learning archive: **18** small console, GUI, automation and data-visualization apps, plus SQLAlchemy ORM notes. PostgreSQL notes kept as runnable `.sql` files - queries, joins, aggregates, transactions, **PL/pgSQL functions and triggers**. | `Python` `tkinter` `PySide6` `requests` `threading` `selenium` `plotly` `psycopg2` `SQLAlchemy` `PostgreSQL` `PL/pgSQL` |

### 🔭 What I'm doing
Working on `event-booking-api`:
- Building the complete test suite
- Closing roadmap items: rate limiting, non-root containers, moving the token lifecycle to Redis

### 🌱 What I'm learning
- Redis
- Django

### 🎯 Next steps
- **Kubernetes and AWS** - the next step after Docker, towards real deployment

### 📫 Contact
Open to junior backend roles, and to any position where I can keep working close to code and keep learning.

Reach me at: **glover012-git@protonmail.com**
