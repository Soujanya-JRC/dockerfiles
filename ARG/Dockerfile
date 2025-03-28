FROM almalinux:9
ENV Fruit="mango" \
    Season="summer"
ARG USERNAME=mangoshake
ARG ${username:-some_user}
RUN echo "Hello user : ${USERNAME}" 
CMD ["sleep" ,"1000"]