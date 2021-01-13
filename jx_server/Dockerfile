FROM centos:latest

# Install basic package for CentOS
RUN yum update -y && \
    yum upgrade -y && \
    yum install epel-release -y && \
    yum install net-tools yum-utils htop vim nano -y

# Install library for JX
RUN yum install -y && \
    yum install -y libuuid.i686 && \
    yum install -y libstdc++.so.6 && \
    yum install -y libcrypto.so.6 && \
    yum install -y libuuid.so.1 && \
    pwd
