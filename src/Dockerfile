FROM node:23.6.1-alpine3.20
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT [ "node", "server.js" ]