FROM node:10.19-jessie

RUN apt-get update && sudo apt-get install -y python gcc make g++ zlib1g-dev python-pip && \
    sudo pip install --upgrade pip setuptools

WORKDIR /usr/app/