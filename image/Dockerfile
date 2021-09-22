FROM node:16.9.0-bullseye-slim

RUN apt-get update && apt-get install -y python gcc make g++ zlib1g-dev python-pip && \
    pip install --upgrade pip setuptools

WORKDIR /usr/app/