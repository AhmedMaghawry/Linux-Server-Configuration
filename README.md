# Linux-Server-Configuration
Udacity full stack nano degree Project 6
 Ip address : http://18.222.37.39/
 SSH port : 22 (Time out when make it 2200)
 Web app url : http://ec2-18-222-37-39.us-east-2.compute.amazonaws.com/
 
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
  * sudo ufw allow 22/tcp
  * sudo ufw allow 80/tcp
  * sudo ufw allow 123/udp
  * sudo ufw enable 
  * sudo dpkg-reconfigure tzdata
  * sudo service apache2 restart
  
# The SSH key for grader
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDWB41QOS6Hw3wXDngGLU6TviQiKTLVQgtYzGjWf8XIchF/ZPcwegQiG0G1RXbLapTpSsQ8MxX7AYLg8Bg75ei+MDWPThE3AhBLjXdH/1oi11Eg0RbUfZRCy1AfAdFAkP0wQ29ZIHIz75IfnjBbOoU73YooBf0Ng3p+tBuo28RWI2mWyh/dkuJZuWT7la3bfy8Pbh8c2O7FLNxiLAiJYUVfFDaXH1f77tzeJAGqdTi6sJUzPpu97W5YcPIFpRL6hfsMUDG5EjTmPGdezuP6e+ckgR6F9k7mS/vCXlEUhA0xKlKx1mA8xQBPhwizscTO1ul8LBjSbuOJZcL+nyQw8Lel ubuntu@ip-172-31-47-74




