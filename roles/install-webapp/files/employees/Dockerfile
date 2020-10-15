FROM s390x/tomcat

COPY data/webapp/employees.war /usr/local/tomcat/webapps

COPY data/conf/server.xml /usr/local/tomcat/conf
COPY data/conf/db.properties /usr/local/tomcat

COPY data/lib/db_driver/db2jcc.jar /usr/local/tomcat/lib
COPY data/lib/db_driver/db2jcc4.jar /usr/local/tomcat/lib
COPY data/lib/db_driver/db2jcc_license_cisuz.jar /usr/local/tomcat/lib

COPY data/lib/encryption/jasypt-1.9.3.jar /usr/local/tomcat/lib

#CMD ["/bin/bash"]
CMD ["/usr/local/tomcat/bin/catalina.sh","run"]
