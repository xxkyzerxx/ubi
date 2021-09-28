FROM confluentinc/cp-server:6.1.3-1-ubi8

USER root

RUN yum update -y && yum upgrade -y && yum clean all

USER appuser

CMD ["/etc/confluent/docker/run"]