FROM node:16

WORKDIR /app

COPY ./abu_server/package*.json ./
RUN npm install

COPY ./abu_server ./

EXPOSE 8001

CMD ["npm", "start"]
