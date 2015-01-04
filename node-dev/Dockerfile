FROM node:latest
MAINTAINER Rashad Majali <rashad.612@gmail.com>

COPY index.js /src/index.js
RUN npm install -g nodemon

WORKDIR /src
ENV NODE_ENV development
EXPOSE 9000
CMD ["nodemon", "index.js"]
