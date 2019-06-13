FROM node:10-jessie

MAINTAINER Lewis Brown "github.com/ramity"

# Update base packages
RUN apt-get update

# Download required deps
RUN npm install -g nativescript

WORKDIR /var/src

ENTRYPOINT tail -f /dev/null
