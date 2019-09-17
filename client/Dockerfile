FROM node:alpine as builder
WORKDIR '/app'
COPY ./package.json ./
RUN npm install react-router-dom
RUN npm install axios
RUN npm install
COPY . .
RUN npm run build