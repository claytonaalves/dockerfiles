# Creates a docker image with python 2.7 and mysql libs
FROM debian:jessie-slim
LABEL maintainer="clayton.aa@gmail.com"

RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get install -y python python-setuptools python-pip
RUN apt-get install -y python-dev libmysqlclient-dev
RUN pip install mysqlclient

