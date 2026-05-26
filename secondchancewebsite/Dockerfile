FROM node:14.17.0-slim

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install --production

COPY . .

EXPOSE 9000

CMD ["node", "index.js"]
