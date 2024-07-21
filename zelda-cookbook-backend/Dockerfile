FROM node:12.22.12-alpine

WORKDIR /app

COPY *.json .

RUN npm install -g knex

RUN npm install --production

COPY . .

RUN chmod +x ./entrypoint.sh

EXPOSE 3000

ENTRYPOINT [ "./entrypoint.sh" ] 

