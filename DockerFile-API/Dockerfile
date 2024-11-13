FROM node:latest

WORKDIR /app

RUN git clone https://github.com/samuelhentrics/SIGLIS-Docker-API .

RUN npm install

EXPOSE 6000

CMD ["node", "./db.js"]
