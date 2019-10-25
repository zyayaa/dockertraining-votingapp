FROM node:10-slim

COPY . /app/
WORKDIR /app/
RUN npm install -g nodemon && npm ci && npm cache clean --force && mv ./node_modules /node_modules
CMD nodemon server.js