# Linux-Server-Configuration
Udacity full stack nano degree Project 6
 Ip address : 34.207.162.217
 SSH port : 2200
 Web app url : http://34.207.162.217/
 
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
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC21JBeKV+xBV33S9gXWzd0G0CyLSO26avAS8+awj77i5k2l49z+BMgVJy4xKqIbRPNQvHM4+8vxRflrqin87biXcgO9GnOHbv7/UR09cAir/qjYPVnXs7V+esqGvWdF+76gEXcG3rIdoe3MahPXCX2tmF78QHKNIpUCVFN5NHUb0ONsrN4mnghycD3sNIL7V43/6ZtrAsfQCrk+zR9AHztpcaih2NVDl4HHRgQoJAP3z30f//KKbYnap2z9QFFesr+/FDmDhWBkdAGIkNlh+KFRSM7LcRFtPP7102iGHOHkpdgW2mdz38BW7wmn4MVMdlPWQr80LqX9a8Uwg8I56zf ubuntu@ip-172-26-9-118





