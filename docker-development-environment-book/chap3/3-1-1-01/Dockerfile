FROM centos:7

RUN yum -y install epel-release

RUN yum -y install nginx

COPY index.html /usr/share/nginx/html

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
