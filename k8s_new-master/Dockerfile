FROM tomcat:8.0

MAINTAINER rajesh

RUN rm -rf /usr/local/tomcat/webapps/

COPY target/mvn-hello-world.war /usr/local/tomcat/webapps/

USER root

WORKDIR /usr/local/tomcat/webapps

EXPOSE 8080

CMD ["catalina.sh", "run"]
