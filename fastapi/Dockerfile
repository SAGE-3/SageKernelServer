FROM python:3.13-slim

RUN apt update
RUN apt upgrade
RUN apt install -y curl
RUN rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY fastapi /app

RUN pip install --no-cache-dir -r requirements.txt
