FROM centos:7
MAINTAINER Adam Bien, adam-bien.com
RUN yum update -y \
  && yum -y install unzip \
  && yum -y install java-1.8.0-openjdk-devel \
  && yum clean all
ENV PATH "$PATH":/${JAVA_HOME}/bin:.: