FROM tomcat:8.0.20-jre8
RUN cp -R /usr/local/tomcat/webapps.dist/* /usr/local/tomcat/webapps/
COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
COPY target/Example-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/sample.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
