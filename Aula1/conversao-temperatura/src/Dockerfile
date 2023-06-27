FROM node:18.16.0

WORKDIR /app

# eficiente para somente rodar o package e npm install caso tenha alterado o package.json
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]
