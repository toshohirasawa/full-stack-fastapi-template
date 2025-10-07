SHELL := /bin/bash

.PHONY: install dev
install:
	uv sync
dev:
	uv run fastapi dev app/main.py --host 0.0.0.0 --reload
