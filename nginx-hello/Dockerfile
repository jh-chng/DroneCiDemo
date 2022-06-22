FROM nginx:mainline-alpine
RUN rm /etc/nginx/conf.d/*
ADD nginx-hello/hello.conf /etc/nginx/conf.d/
ADD nginx-hello/index.html /usr/share/nginx/html/
