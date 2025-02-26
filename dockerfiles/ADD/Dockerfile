FROM almalinux:9
RUN dnf -y install nginx
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/DevOpsAWSNotes/dockerfiles/refs/heads/main/dockerfiles/FROM/Dockerfile  /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]