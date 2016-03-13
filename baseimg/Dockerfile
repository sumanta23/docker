FROM ubuntu:14.04

RUN apt-get update && apt-get install -y \
        ca-certificates \
        curl \
        wget \
        git  \
        openssh-server \
        python2.7

ENV LANG C.UTF-8

COPY jdk1.7.0_75/ /opt/sw/java7

ENV JAVA_HOME /opt/sw/java7

ENV PATH $JAVA_HOME/bin:$PATH
