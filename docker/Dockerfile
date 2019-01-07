FROM debian:stretch
LABEL maintainer="PRONTO Developers <dev@pronto.org>"
LABEL description="Dockerised PRONTOCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
