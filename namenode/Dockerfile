FROM bde2020/hadoop-namenode:2.0.0-hadoop3.2.1-java8

RUN apt-get update

RUN apt-get install -y python

COPY ./example /root
COPY ./*.jar /root/

