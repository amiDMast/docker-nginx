FROM nginx:latest

RUN mv /etc/nginx/nginx.conf /etc/nginx/nginx.conf~orig

COPY ./nginx.conf /etc/nginx/
COPY ./default.conf /etc/nginx/conf.d/