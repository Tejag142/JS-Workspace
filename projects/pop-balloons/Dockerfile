FROM almalinux:9
RUN dnf update -y && dnf install nginx -y
COPY . /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]