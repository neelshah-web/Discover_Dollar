# Stage 1: Build the Angular application
FROM node:18.19.1 as build

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .
RUN npm run build
