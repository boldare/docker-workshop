FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install python -y
RUN apt-get install python-numpy -y

ADD app.py

CMD python app.py
