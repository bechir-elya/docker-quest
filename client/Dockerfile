FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src src
COPY public/ public/
COPY index.html ./
COPY vite.config.js ./

CMD [ "npm", "start" ]