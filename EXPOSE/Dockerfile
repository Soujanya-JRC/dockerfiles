FROM  almalinux:9
RUN dnf install nginx -y
# there is no functionality for EXPOSE, just for information purpose
EXPOSE 80
CMD ["nginx", "-g", "daemon-off;"]