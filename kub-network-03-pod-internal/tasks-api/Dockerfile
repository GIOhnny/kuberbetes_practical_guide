FROM node:14-bullseye-slim

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8000

CMD [ "node", "tasks-app.js" ]