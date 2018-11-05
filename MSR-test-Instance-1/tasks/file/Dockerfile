FROM centos
MAINTAINER Mayank Bhogal
RUN yum -y install httpd
RUN yum install httpd httpd-tools -y
RUN yum clean all
#ADD apache2.conf /etc/apache2/apache2.conf
COPY index.html /var/www/html/index.html
COPY run.sh run.sh
#RUN ["chmod", "+x", "/run.sh"]
CMD ./run.sh

