#Base Image.
FROM tomcat:8.0


# Inject Petclinic War File
COPY petclinic.war /usr/local/tomcat/webapps/

#Base Image
FROM centos:7


#Inject html file

COPY info.html /var/www/html/info.html
