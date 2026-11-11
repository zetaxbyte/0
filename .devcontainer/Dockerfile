FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

WORKDIR /root

RUN apt-get update && apt-get install -y sudo \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

RUN echo 'export PS1="\u:\w# "' >> /root/.bashrc
