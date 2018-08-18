FROM    bitnami/centos:latest

RUN yum -y update && yum -y install openldap compat-openldap openldap-clients openldap-servers


EXPOSE  389
EXPOSE  636


CMD     ["/bin/bash"]

