FROM almalinux:9
ENV Fruit="mango" \
    Season="summer"
# here user1 is key and someuser is default value
ARG ${username:-some_user}
RUN echo "Hello user : ${username}" 
CMD ["sleep" ,"1000"]