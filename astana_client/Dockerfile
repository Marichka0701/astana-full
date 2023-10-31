FROM nginx:alpine
WORKDIR /app

COPY astana_client/build /usr/share/nginx/html

EXPOSE 81

CMD ["nginx", "-g", "daemon off;"]
