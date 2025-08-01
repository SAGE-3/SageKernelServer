FROM python:3.13-slim

RUN apt update && apt install -y curl && rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY fastapi /app

RUN pip install --no-cache-dir -r requirements.txt
