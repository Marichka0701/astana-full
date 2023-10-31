FROM nginx:alpine


COPY client/build /usr/share/nginx/html
COPY client/default.conf /etc/nginx/conf.d/

EXPOSE 83

CMD ["nginx", "-g", "daemon off;"]
