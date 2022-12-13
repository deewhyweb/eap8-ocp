FROM quay.io/wildfly/wildfly-runtime-jdk11:latest
COPY --chown=jboss:root server $JBOSS_HOME
RUN chmod -R ug+rwX $JBOSS_HOME