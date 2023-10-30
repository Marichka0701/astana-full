FROM node:16

WORKDIR /app

COPY ./saudi_server/package*.json ./
RUN npm install

COPY ./saudi_server ./

EXPOSE 8002

CMD ["npm", "start"]
