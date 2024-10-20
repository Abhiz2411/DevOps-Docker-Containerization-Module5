FROM python:3.9-slim

WORKDIR /mydbapp

COPY . .

RUN pip install PyMySQL
RUN pip install cryptography

CMD [ "python", "sql_demo.py" ]