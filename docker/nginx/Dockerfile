FROM nginx:1.20
COPY ./docker/nginx/default.conf /etc/nginx/conf.d/default.conf
COPY ./docker/nginx/nginx.conf /etc/nginx/nginx.conf
COPY ./src /var/www/html
ENV TZ Asia/Tokyo
EXPOSE 80