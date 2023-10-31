FROM nginx:alpine
WORKDIR /app

COPY astana_client/build /usr/share/nginx/html
COPY astana_client/default.conf /etc/nginx/conf.d/

EXPOSE 81

CMD ["nginx", "-g", "daemon off;"]
