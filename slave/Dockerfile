# The FROM will be replaced when building in OpenShift
FROM openshift/jenkins-slave-base-rhel7

ADD ./configuration/settings.xml $HOME/.m2/

RUN chown -R 1001:0 $HOME && \
    chmod -R g+rw $HOME

USER 1001
