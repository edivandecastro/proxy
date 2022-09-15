FROM node:16

WORKDIR /usr/src/app

COPY /nodejs/server.js ./
COPY /nodejs/package*.json ./

RUN npm install

CMD [ "node", "server.js" ]
