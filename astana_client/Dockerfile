FROM node:16 AS build

WORKDIR /app

COPY ./astana_client/package*.json ./
RUN npm install

COPY ./astana_client ./

FROM nginx:alpine

COPY --from=build /app/build /usr/share/nginx/html

EXPOSE 81

CMD ["nginx", "-g", "daemon off;"]
