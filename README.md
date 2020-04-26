                                     By usiing Docker Creating The SSH-SERVER

by using Docker I create one ssh-server and using this server I create one architecture. The architecture I created is show in the one architecture image file ther you can see the architecture of project .

Steps:

1. Check the Architecture File For Understanding The Project or What actually we are Doing in Project

2.Dockerfile - docker file is creating the ssh-server Image                                                                          
  .Dockerfile where there you have to run below command
  .$ docker build -t name/centos:7 .  --name , you can give any name like sumit,krushna what ever you want. 
  
3.Start the docker 
    .$ systemctl start docker
    
4. run the yml file 
    . $ docker-compose up 

