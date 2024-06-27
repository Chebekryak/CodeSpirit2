FROM python:3.12.4-slim

COPY requirements.txt ./application/requirements.txt

RUN pip install --upgrade pip

RUN pip install -r ./application/requirements.txt

COPY . ./application

WORKDIR /application
