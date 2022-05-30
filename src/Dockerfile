FROM node:18

ENV NODE_ENV=$NODE_ENV

COPY ./ /home/node/app

WORKDIR /home/node/app

RUN npm install

EXPOSE 3000

CMD npm start