FROM pytorch/pytorch:1.13.0-cuda11.6-cudnn8-devel

SHELL ["/bin/bash", "-c"]

RUN apt-get update
ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get install -y git jupyter-notebook
