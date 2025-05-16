FROM node:20-alpine

WORKDIR /app

COPY package.json package.json

RUN npm install

EXPOSE 80

COPY . .

CMD ["node", "server.js"]