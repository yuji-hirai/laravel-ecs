FROM nginx:1.20-alpine
COPY ./docker/nginx/default.conf /etc/nginx/conf.d/default.conf
COPY ./docker/nginx/nginx.conf /etc/nginx/nginx.conf
COPY ./docker/nginx/htpasswd /etc/nginx
COPY ./src /var/www/html
ENV TZ Asia/Tokyo
EXPOSE 80