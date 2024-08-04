# AWS
COMMANDS:
java version changing :          update-alternatives --config java 










LINKS : tomcat 8 link - wget http://archive.apache.org/dist/tomcat/tomcat-8/v8.0.23/bin/apache-tomcat-8.0.23.tar.gz


*USERDATA*
#!/bin/bash
sudo yum install -y git
sudo yum install -y httpd
sudo systemctl start httpd
sudo systemctl enable httpd
sudo git clone https://github.com/Akiranred/ecomm.git /var/www/html
