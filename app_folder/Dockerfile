FROM python:3.10.2-slim

COPY . /app
WORKDIR /app

RUN pip install --upgrade pip && pip install flask art
ENV Name="Leo"

ENTRYPOINT ["python", "app.py"]