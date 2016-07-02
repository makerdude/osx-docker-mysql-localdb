# osx-docker-mysql-localdb
Using a local directory host mapped to docker instead of using a docker volume for persistent storage of mysql db


If you try and  map a local directory as /var/lib/mysql, it doesn't work.  Normally, for persistent storage, 
you use a docker volume.  



This repository contains a fix how how to do that.  

