FROM node:18

WORKDIR /docker-compose

COPY  ["package.json","package-lock.json", "./"]

RUN npm install

COPY . .

EXPOSE 3000

CMD npm start