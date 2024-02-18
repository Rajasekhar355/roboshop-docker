FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /user/share/nginx/html/index.html
# FROM LOCAL TO IMGE
ADD index.html /usr/share/nginx/html/
# FROM URL can download and copy TO IMG
ADD "www.google.com/index.html" /usr/share/nginx/html/
# tar file can directly extract
ADD "www.google.com/index.tar" /usr/share/nginx/html/