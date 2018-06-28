FROM jenkins/jenkins:lts
USER root
RUN apt-get update \
&& apt-get install -y ruby \
&& apt-get -y install openssh-server \
&& apt-get -y install vim \
&& apt-get -y install net-tools 
USER jenkins