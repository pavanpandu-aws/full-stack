FROM tomcat:latest

COPY backend.war /usr/local/tomcat/webapps/ROOT.war

RUN rm -rf /usr/local/tomcat/webapps/ROOT

EXPOSE 8080

CMD ["catalina.sh", "run"]