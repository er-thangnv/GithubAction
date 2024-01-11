FROM node:20-alpine

WORKDIR /home/nvthang/Documents/DockerExample/docker-nodejs-sample

COPY package*.json ./

RUN npm install

EXPOSE 5050

CMD [ "node src/index.js" ]
