FROM node

WORKDIR /node-app

COPY node-app/package.json /node-app

RUN npm install

COPY node-app/. /node-app

EXPOSE 3000

CMD ["node", "server.js"]