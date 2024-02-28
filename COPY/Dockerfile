FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/shared/ngins/html/index.html
COPY index.html /usr/shared/ngins/html/
CMD ["nginx","-g","daemon off;"]