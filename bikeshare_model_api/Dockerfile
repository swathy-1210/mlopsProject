# Use the official Python image
FROM python:3.8-slim

WORKDIR /app

COPY . /app

RUN pwd & ls -lrt & cd /app & ls -lrt & pip install -r requirements.txt

CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "80"]
