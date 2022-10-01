FROM centos:7

RUN yum -y install epel-release

RUN yum -y install nginx

COPY index.html /usr/share/nginx/html

RUN ln -sf /dev/stdout /var/log/nginx/access.log && ln -sf /dev/stderr /var/log/nginx/error.log

ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
