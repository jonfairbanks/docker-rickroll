FROM nginx:stable-alpine

RUN cp MP4/4k/rickroll.mp4 test/src/rickroll.mp4
COPY test/src/ /usr/share/nginx/html/
COPY test/conf/nginx-site.conf /etc/nginx/conf.d/default.conf

EXPOSE 80 8080
