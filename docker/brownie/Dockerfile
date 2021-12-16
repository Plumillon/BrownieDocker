FROM python:3.7

# Set up code directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Install linux dependencies
RUN apt-get update && apt-get install -y libssl-dev

RUN apt-get update && apt-get install -y \
    npm

RUN npm install -g ganache-cli

RUN apt update
RUN apt -y upgrade
RUN apt install -y python3-pip
RUN pip3 install eth-brownie