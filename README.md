# SSh-Server By Using Docker 

**Architecture Of Project**
![job2](https://github.com/Sumit-Rasal/SSH-Server-By-Docker/blob/master/Architecture.jpg)
 
by using Docker I create one ssh-server and using this server I create one architecture. The architecture I created is show in the one architecture image file ther you can see the architecture of project .

**Steps For The Launching Ssh-SERVER Environment** 

**Step-1.**
* Check the Architecture File For Understanding The Project.What actually we are Doing in Project

**Step-2.** Dockerfile - docker file is creating the ssh-server Image
                                                                          
 * Dockerfile where there you have to run below command
 ```
 $ docker build -t name/centos:7
 ``` 
 * --name , you can give any name like sumit, krushna whatever you want. 
  
**Step-3.** 
* Start the docker 
```
     $ systemctl start docker
 ```
    
**Step-4.**
* run the yml file : yml File is For The Launching The Enviroment That We Created.
 ```
     $ docker-compose up 
 ```
