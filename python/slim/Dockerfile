FROM python:3.8.1-slim

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    apt-utils \
    gcc \
    build-essential \
    && pip install --no-cache-dir \
    autopep8 \
    flake8 \
    pylint \
    mypy \
    && apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*
