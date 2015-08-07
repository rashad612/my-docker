FROM node:latest
MAINTAINER Rashad Majali <rashad.612@gmail.com>

RUN npm install -g bower
RUN echo '{ "allow_root": true }' > /root/.bowerrc
RUN npm install -g nodemon

ENV NODE_ENV development

WORKDIR /src
