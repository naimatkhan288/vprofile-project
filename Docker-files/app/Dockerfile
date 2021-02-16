FROM tomact:8-jre11

LABEL "Project"="Vprofile"
LABEL "Author"="Imran"

RUN rm -rf /usr/local/tomcat/webapps/*

COPY target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080

CMD ["catalina", "run"]

WORKDIR /usr/local/tomcat/

VOLUME /usr/local/tomcat/webapps