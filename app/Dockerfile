# syntax=docker/dockerfile:1
FROM node:12-alpine
WORKDIR /app
COPY package.json yrm.lock ./
RUN yarn install --production
COPY . .
CMD ["node", "src/index.js"]