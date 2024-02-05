FROM pytorch/pytorch:2.2.0-cuda12.1-cudnn8-devel

SHELL ["/bin/bash", "-c"]

RUN apt-get update
ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get install -y git jupyter-notebook
