FROM    bitnami/centos:latest

RUN yum -y update && yum -y install openldap compat-openldap openldap-clients openldap-servers

EXPOSE  389 636

COPY entrypoint.sh /usr/local/bin/entrypoint.sh

ENTRYPOINT ["entrypoint.sh"]

CMD     ["/bin/bash"]

