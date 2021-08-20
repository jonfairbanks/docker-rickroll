FROM nginx:stable-alpine

RUN cp ./MP4/rickroll.mp4 src/rickroll.mp4
COPY src/ /usr/share/nginx/html/
COPY conf/nginx-site.conf /etc/nginx/conf.d/default.conf

EXPOSE 80 8080
