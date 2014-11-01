# Dockerizing MongoDB:
# based on debian wheezy, and the installation of mongodb for debian

# Pull debian base image
FROM google/debian:wheezy

MAINTAINER Giovanni Damiola <gdamiola@belzem.org>

# Installing main packages customizing the debian distro

RUN apt-get update
RUN apt-get install -y apt-utils
RUN apt-get install -y sysv-rc procps adduser python3
