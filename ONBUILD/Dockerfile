FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/index.html
#this executes if any user uses your image as their base OS
ONBUILD Copy index.html  /usr/share/nginx/index.html
CMD ["nginx", "-g", "daemon off;"]