FROM python:3.12.7-alpine

COPY . /app/
WORKDIR /app

RUN pip install -r requirements.txt

CMD ["/bin/sh", "boot.sh"]
