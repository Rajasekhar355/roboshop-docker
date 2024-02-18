FROM almalinux:8
RUN yum install nginx -y
ENTRYPOINT["ping", "google.com"]

#docker build -t entrypoint:v1
#docker run cmd:v1 ping yahoo.com =----->    It gives error it will not allow to overide when using ENTERPOINT
# check docker ps -a --trunca

#Best practice to use CMD and ENTRYPOINT combination
CMD ["google.com"]
ENTRYPOINT["ping"]

# docker build -t entrypoint:v1
# docker run entrypoint:v1

# docker run entrypoint:v1 yahoo.com