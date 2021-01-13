FROM centos:latest

# Install basic package for CentOS
RUN yum update -y && \
    yum upgrade -y && \
    yum install epel-release -y && \
    yum install net-tools yum-utils htop vim nano -y

# Install library for JX
# Use exit 0 to make sure command will always success and wont interrupt the build process
RUN yum install -y libuuid.i686; exit 0 && \
    yum install -y libstdc++.so.6; exit 0 && \
    yum install -y libcrypto.so.6; exit 0 && \
    yum install -y libuuid.so.1; exit 0