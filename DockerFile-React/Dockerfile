FROM node:latest

WORKDIR /app

# Clone le repo et vérifie la fin du téléchargement
RUN git clone https://github.com/samuelhentrics/SIGLIS-Docker-Front .

# Installe les dépendances
RUN npm install

# Build le projet
RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]
