FROM confluentinc/cp-schema-registry:6.1.2-2-ubi8

USER root

RUN yum update -y && yum upgrade -y && yum clean all

USER appuser

CMD ["/etc/confluent/docker/run"]