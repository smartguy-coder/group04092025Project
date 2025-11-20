uv run alembic init migrations
alembic revision --autogenerate -m "initial migration"
alembic upgrade head
alembic downgrade -1