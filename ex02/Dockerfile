FROM python:3.9-slim

WORKDIR /tmp/mydir

COPY ex02/requirements.txt ${PWD}

RUN pip install -r requirements.txt

ARG wdir

WORKDIR $wdir