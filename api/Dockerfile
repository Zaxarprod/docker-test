FROM node:10

WORKDIR /usr/src/app/api

COPY package*.json ./

RUN yarn install

EXPOSE 3080

RUN yarn build

CMD ["yarn", "start"]