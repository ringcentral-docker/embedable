FROM node:14.19.0

RUN apt-get update && apt-get install -y python gcc make g++ zlib1g-dev python-pip && \
    pip install --upgrade pip setuptools

WORKDIR /usr/app/