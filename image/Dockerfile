FROM centos
RUN yum install httpd -y
COPY index.html /var/www/html/index.html
COPY run.sh / 
RUN chmod +x /run.sh 
CMD /run.sh
