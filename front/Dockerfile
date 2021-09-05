FROM node:14.17.6-alpine

ENV APP_HOME /app
RUN mkdir -p $APP_HOME
WORKDIR $APP_HOME

RUN apk update && npm install -g @vue/cli
COPY package.json .
RUN npm install