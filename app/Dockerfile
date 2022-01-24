FROM python:3.9-alpine



WORKDIR /app
RUN apk update && apk add gcc libc-dev make git libffi-dev openssl-dev python3-dev libxml2-dev libxslt-dev 

COPY requirements.txt /app
RUN pip install -r requirements.txt

COPY app.py /app

