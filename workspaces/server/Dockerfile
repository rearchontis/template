FROM node:18-alpine

WORKDIR /usr/src/app

COPY package*.json ./

# RUN npm i -g npm

RUN npm ci

COPY . .
