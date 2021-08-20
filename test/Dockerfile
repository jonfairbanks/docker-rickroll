FROM nginx:stable-alpine

COPY src/ /usr/share/nginx/html/
COPY MP4/rickroll.mp4 /usr/share/nginx/html/rickroll.mp4
COPY conf/nginx-site.conf /etc/nginx/conf.d/default.conf

EXPOSE 80 8080
