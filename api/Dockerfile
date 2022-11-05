FROM python:2

ENV PYTHONUNBUFFERED 1

WORKDIR /api

ADD . /api

COPY ./requirements.txt /api/requirements.txt

RUN pip install -r requirements.txt

COPY . /api

