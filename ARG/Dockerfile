FROM almalinux:9
ENV Fruit="mango" \
    Season="summer"
# here user1 is key and someuser is default value
ARG ${fruitsale:-some_user}
RUN echo "summer special ${fruitsale} shake" > /tmp/fruits.txt
CMD ["sleep" ,"100"]