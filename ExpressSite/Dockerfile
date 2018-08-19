FROM node:latest

MAINTAINER Dash Sat

ENV NODE_ENV=production PORT=3000

COPY . /var/www
WORKDIR /var/www

RUN npm install

EXPOSE $PORT

ENTRYPOINT [ "npm", "start" ]

