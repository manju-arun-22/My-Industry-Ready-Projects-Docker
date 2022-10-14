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

 #8 
 ```
	docker commit
 ```
 
 docker commit <conatainer id> <username/imagename>
 
 This command creates a new image of an edited container on the local system

 ![image](https://user-images.githubusercontent.com/112603638/195577221-08391be1-b4c5-4de5-b333-dcb1f7f8614b.png)


 #9
 ```
  docker login
 ```
 
This command is used to login to the docker hub repository

 ![image](https://user-images.githubusercontent.com/112603638/195577336-0889ad43-f310-4086-9d17-92eda7b35fd9.png)

 #10
 
 ```
 docker push
 ```
 
 docker push <username/image name>
 
 This command is used to push an image to the docker hub repository
 ![image](https://user-images.githubusercontent.com/112603638/195577513-f78643c8-2da8-4af4-b55f-1d451e637514.png)


#11
```
docker images
```

This command lists all the locally stored docker images.

![image](https://user-images.githubusercontent.com/112603638/195679319-5d863e4e-2682-42f2-8baf-a3b0b4566587.png)


#12
```
docker rm
```

docker rm <container id>
This command is used to delete a stopped container.
![image](https://user-images.githubusercontent.com/112603638/195679459-720f8ad8-d24f-4288-82e5-71cc411d845a.png)


#13
```
docker rmi
```
docker rmi <image-id>
This command is used to delete an image from local storage.

![image](https://user-images.githubusercontent.com/112603638/195679596-4f71a88d-1b0f-4dbc-bc3d-81b6707654e3.png)
 
#14
```
docker build
```

This command is used to build an image from a specified Dockerfile

![image](https://user-images.githubusercontent.com/112603638/195679713-ba769814-add4-44b1-a1a4-f3e8e6517b3e.png)

#15 
```
docker start
```
docker start <containerid>
command used to start a stopped container

![image](https://user-images.githubusercontent.com/112603638/195680270-e97510d1-89c3-4241-8079-02bc694a6291.png)


Assignment 2:
Hello World Docker Image Run Hello World Docker Image Locally.
```
docker pull hello-world
```
```
docker run hello-world
```
![image](https://user-images.githubusercontent.com/112603638/195885254-b4f6d9f9-e205-47a2-ae93-5b55d1cb830c.png)






 
