FROM centos:latest

# Install basic package for CentOS
RUN yum update -y && \
    yum upgrade -y && \
    yum install epel-release -y && \
    yum install net-tools yum-utils htop vim nano -y

# Install library for JX
RUN yum install -y libuuid.i686 libstdc++.so.6 libcrypto.so.6 libuuid.so.1