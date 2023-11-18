FROM  python:3.11.6-bookworm

ENV PYTHONUNBUFFERED=1

WORKDIR /api

COPY . . 

RUN pip install -r requirements.txt

EXPOSE 8000