FROM ubuntu
MAINTAINER Mithilesh
WORKDIR /mithi
RUN apt-get update
ADD https://tomcat.apache.org/tomcat-7.0-doc/appdev/sample/sample.war /mithi/
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.65/bin/apache-tomcat-9.0.65.zip /mithi/
EXPOSE 8080
