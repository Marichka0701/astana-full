FROM nginx:alpine

COPY saudi_client/build /usr/share/nginx/html
COPY saudi_client/default.conf /etc/nginx/conf.d/

EXPOSE 82

CMD ["nginx", "-g", "daemon off;"]
