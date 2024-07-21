FROM node:8.11.0-alpine

WORKDIR /app

COPY *.json .

RUN npm install

COPY . .

CMD [ "npm","start" ]