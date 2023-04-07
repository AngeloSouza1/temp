FROM node:14 AS builder

WORKDIR /app

COPY . .

 RUN npm i

RUN chmod +x wait-for-it.sh

EXPOSE 3000

CMD [ "npm", "start" ]
