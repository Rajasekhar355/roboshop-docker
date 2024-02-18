FROM almalinux:8
RUN yum install nginx -y
# Adding metadata to an image
LABEL USER=RAJ \
      COURSE=DEVOPS \
      TRAINING=DOCKER  
CMD ["nginx", "-g", "daemon off;"]

#docker images --filter label=USER=RAJ

