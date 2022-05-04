FROM node:alpine
COPY package*.json ./
RUN npm install

COPY . /app
WORKDIR /app
CMD node app.js