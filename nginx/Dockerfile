FROM debian:stretch-backports


LABEL description="Debian Jessie nchan server"
MAINTAINER Ignacio Núñez Hernanz <nacho@ownyourbits.com>


RUN apt-get update && apt-get -y upgrade && apt-get -y install nginx-extras libnginx-mod-nchan

EXPOSE 80

CMD /usr/sbin/nginx -g 'daemon off;'

