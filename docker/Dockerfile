FROM debian:stretch
LABEL maintainer="Btcgreen Developers <dev@btcgreen.org>"
LABEL description="Dockerised BtcgreenCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
