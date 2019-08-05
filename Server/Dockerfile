FROM ubuntu:14.04
MAINTAINER wh136 <136856026@qq.com>
RUN apt-get -y update && \
    apt-get install -y python-dev python-paramiko python-setuptools git python-pip
RUN apt-get -y build-dep python-libtorrent

RUN pwd
WORKDIR /opt/ansible/ansible

ENV PATH /opt/ansible/ansible/bin:/bin:/usr/bin:/sbin:/usr/sbin
