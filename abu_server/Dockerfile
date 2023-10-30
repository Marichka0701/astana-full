FROM node:16

WORKDIR /app

COPY ./astana_server/package*.json ./
RUN npm install

COPY ./astana_server ./

EXPOSE 8003

CMD ["npm", "start"]
