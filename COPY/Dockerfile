FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/shared/nginx/html/index.html
COPY index.html /usr/shared/nginx/html/
CMD ["nginx","-g","daemon off;"]