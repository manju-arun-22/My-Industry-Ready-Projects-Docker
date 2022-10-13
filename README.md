# Industry-Ready-Projects-Assignment-2
# Docker & Docker Hub
### Assignment 1:

Demonstrate minimum 15 basic docker command with explanation and screenshot.

#1 
```
docker pull
```
 docker pull <image name> : use to pull image from docker hub
 ![image](https://user-images.githubusercontent.com/112603638/195422626-6f4620f8-5562-4952-9532-0fb179bfb18f.png)

#2
```
docker run
```
docker run used to create container from an image
eg : docker run -it -d mongo
![image](https://user-images.githubusercontent.com/112603638/195422292-c1016848-9d27-4076-9a7c-68819831d8a8.png)

#3
```
docker ps
```
docker ps command is used to list running containers
![image](https://user-images.githubusercontent.com/112603638/195424185-48bf2b88-4bbc-47fb-acd4-2c45867644c8.png)

 #4
 
 ```
 docker ps -a
 
 ```
 docker ps -a command is used to list all the containers
 
 ![image](https://user-images.githubusercontent.com/112603638/195424549-db3e24c0-f584-4103-9db9-07fd34f66ac1.png)
 
 #5
 
 ```
 docker exex
 
 ```
docker exec -it <container id> bash

 This command is used to access the running container
 
![image](https://user-images.githubusercontent.com/112603638/195526104-2018848e-001e-4548-93a5-1254b6134c6b.png)

 #6
 ```
 docker stop
 ```
docker stop < container id>
 
This command is used to stop a running container
 
![image](https://user-images.githubusercontent.com/112603638/195528688-6a793281-bc87-4af7-9283-53ce04da127d.png)

 #7
 ```
 docker kill
 ```
docker kill <container id>
 
This command stops the container immediately
 
Docker stop command gives the container time to shutdown gracefully.
But when it is taking too much time for getting the container to stop, we can opt to kill it.

 ![image](https://user-images.githubusercontent.com/112603638/195529842-2c29b606-d9b9-4614-8eea-1b8fd8c1463a.png)

 




 
