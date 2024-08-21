FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
COPY https://raw.githubusercontent.com/Devopslearning2025/27.Docker/main/ADD/Dockerfile /tmp/add.txt
CMD ["nginx", "-g","daemon off;"]