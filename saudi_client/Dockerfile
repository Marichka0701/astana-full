FROM node:16 AS build

WORKDIR /app

COPY ./saudi_client/package*.json ./
RUN npm install

COPY ./saudi_client ./

FROM nginx:alpine

COPY --from=build /app/build /usr/share/nginx/html

EXPOSE 82

CMD ["nginx", "-g", "daemon off;"]
