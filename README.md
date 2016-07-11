At first, in this progect I installed Vagrant and Virtualbox:
![alt text](https://github.com/antontkachenka/vagrant/blob/master/source/1.png "Pic 1")
After I installed two VM, wich act as front-end (web) and back-end (app) servers:
![alt text](https://github.com/antontkachenka/vagrant/blob/master/source/2.png "Pic 2")
After that I wrote script, wich automaticaly deploy httpd and tomcat servers, connected them on servers wich I installed erlier (web and app). On last screenshot I showed that we can connect to web server over IP and get tomcat's start-page: 
![alt text](https://github.com/antontkachenka/vagrant/blob/master/source/8.png "Pic 3")

Directory "sourse" contains only screenshots for task. 

File "vagrantfile" contains config for deployment two VM over Virtualbox.

File "web.sh" contains scripts for deployment httpd and mod_jk. 

File "app.sh" contains scripts for deployment tomcat.
