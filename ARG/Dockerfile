FROM almalinux:9
ENV Fruit="mango" \
    Season="summer"
ARG USERNAME=mangoshake
ARG ${username:-some_user}
RUN echo "Hello user : ${USERNAME}" /tmp/devops.txt
CMD ["sleep" ,"1000"]