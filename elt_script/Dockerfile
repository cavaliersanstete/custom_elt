FROM python:3.8-slim

RUN apt-get updated && apt-get -y postgresql-client

COPY elt_script.py .

CMD ["python", "elt_script"]