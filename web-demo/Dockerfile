FROM 192.168.111.138/kubernetes/tomcat:v1

COPY ROOT /usr/local/tomcat/webapps/ROOT

COPY dockerfiles/start.sh /usr/local/tomcat/bin/start.sh

ENTRYPOINT ["sh" , "/usr/local/tomcat/bin/start.sh"]
