FROM nginx:alpine

COPY default.conf /etc/nginx/conf.d/
COPY page.html /usr/share/nginx/html/