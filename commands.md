#Install Tomcat
- wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.84/bin/apache-tomcat-9.0.84.tar.gz

#Untar file
tar -zvxf apache-tomcat-9.0.84.tar.gz

#navigate to bin folder
cd /home/ec2-user/apache-tomcat-8.5.96/bin/

Install Java
- yum install java-11 -y

#find / --name context.xml
/home/ec2-user/apache-tomcat-9.0.84/conf/context.xml
/home/ec2-user/apache-tomcat-9.0.84/webapps/docs/META-INF/context.xml
/home/ec2-user/apache-tomcat-9.0.84/webapps/examples/META-INF/context.xml
/home/ec2-user/apache-tomcat-9.0.84/webapps/host-manager/META-INF/context.xml
/home/ec2-user/apache-tomcat-9.0.84/webapps/manager/META-INF/context.xml



