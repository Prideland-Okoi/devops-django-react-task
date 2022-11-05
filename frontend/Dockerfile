FROM node:16-alpine

WORKDIR /frontend

COPY package.json .

RUN npm install -g npm@8.19.3

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]