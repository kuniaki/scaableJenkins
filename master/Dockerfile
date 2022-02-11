#FROM jenkins/jenkins:alpine
FROM jenkins/jenkins:latest

#install Plugin
COPY plugin.txt /usr/share/jenkins/ref/
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugin.txt

VOLUME /var/jenkins_home

USER jenkins
