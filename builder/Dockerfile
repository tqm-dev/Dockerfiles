FROM ubuntu:16.04

RUN apt-get clean
RUN apt update
RUN apt upgrade -y

RUN apt-get install -y vim patch python

RUN apt-get install -y sed wget git-core coreutils unzip texi2html texinfo \
libsdl1.2-dev docbook-utils fop gawk python-pysqlite2 diffstat make gcc \
build-essential xsltproc g++ desktop-file-utils chrpath libgl1-mesa-dev \
libglu1-mesa-dev autoconf automake groff libtool xterm libxml-parser-perl

WORKDIR /work
