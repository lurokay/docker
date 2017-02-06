FROM debian:jessie
MAINTAINER Lukas Krueck <git@lukaskrueck.de>

RUN apt-get update && apt-get upgrade -y --force-yes && apt-get install -y --force-yes --no-install-recommends apt-utils
RUN echo Europe/Berlin > /etc/timezone && dpkg-reconfigure tzdata
