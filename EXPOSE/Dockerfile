FROM almalinux:9
RUN dnf install nginx -y && dnf clean all
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]