FROM node:10

WORKDIR /usr/src/app/my-app

COPY package*.json ./

RUN yarn install

EXPOSE 3000

RUN yarn build

CMD ["yarn", "start"]