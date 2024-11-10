FROM nginx:latest

WORKDIR /usr/nginx/www/html/

COPY . .

EXPOSE 80

ENV PORT=80

CMD [ "nginx", "-g", "daemon-off" ]