FROM jupyter/datascience-notebook:latest

USER root
COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

WORKDIR /home/jovyan/work/