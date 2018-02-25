# Linux-Server-Configuration
Udacity full stack nano degree Project 6
 Ip address : 34.207.162.217
 SSH port : 2200
 Web app url : http://34.207.162.217/
 Grader sudo password : Ahmed
 
# Software Installed
  * Apache2 ``` sudo apt-get install apache2 ```
  * Python tools ``` sudo apt-get install python-setuptools libapache2-mod-wsgi ```
  * PostgreSQL ``` sudo apt-get install postgresql ```
  * Git ``` sudo apt-get install git ```
  * Sql Alchemy ``` sudo pip install sqlalchemy flask-sqlalchemy psycopg2 bleach requests ```
  * Flask ``` sudo pip install flask packaging oauth2client redis passlib flask-httpauth ```
  * psycopg2 ``` sudo apt-get -qqy install postgresql python-psycopg2 ```

# Some Configurations
  * sudo ufw allow ssh
  * sudo ufw allow www
  * sudo ufw allow ntp
  * sudo ufw allow 2200/tcp
  * sudo ufw allow 80/tcp
  * sudo ufw allow 123/udp
  * sudo ufw enable 
  * sudo dpkg-reconfigure tzdata
  * sudo service apache2 restart
  
# The SSH key for grader
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC4GZ6kktmcl1hHD+MXZG3AcQYSE84sv8tmlKTg0wb032H4h7Oi/I1IE9ec+WguZWY1Rx2zH/zcV3xe6uX3XVMC6TyMawFDoDRE3wt3n2fjCXaGCQmqWabSpCH2FLtiq4+OEOVL9hpahytFER0Ve6u1k1r+I4jhC9oJc4e8/fBQ1CmhMgRXMH5s/H48vem8NtcA0WqHbonQDnMa3YI6BBlcf6lGLwQMooxP8fGqo9YlInI9P7DHpc781xniS4hxOXiNAWUMTE5rNc2iaURXMKNxXmJFvGbnddaUs/B8ehV1ar1/B8/ceqJmG/MZDGIxtkpdnAW1vq0efgPIexVIIxYl default@ezzat





