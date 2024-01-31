FROM ubuntu:22.04

RUN apt update && apt -y upgrade
RUN apt -y install git python3 python3-pip
COPY requirements.txt /
RUN pip3 install -r /requirements.txt