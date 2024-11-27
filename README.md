# 2048-python-game-dockerfile
A dockerfile created to build an image to run container which contains the source code and dependencies required for the python application to run.

**Prerequisite:** 
1. Linux/Windows OS (I have used Linux Ubuntu)
2. Docker & Git installed on your machine

**Steps to run dockerfile are given below:** 
Step 1: Open VS Code

Step 2: Save the dockerfile naming **Dockerfile**

Step 3: Build an docker using dockerfile 
        Command : **docker build .**     

Step 4: After the image is build, run the following command to build a container
        Commmand: **docker run -d -p 80 <image-name/id>**
        where -p is port and 80 is the port number as I am running the container on port 80 of localhost

Step 5: After running the command you will get the container id

Step 6: To check whether the conatiner/image is build use the following command
        Command: For docker image: **docker images**
                 For docker container: **docker ps**

Step 7: If docker conatiner is build successfully use the follwoing command                 
        Command: **docker start <container-name/id>**

Step 8: If docker container is successfully created than you will get the conatiner id

Step 9: Go to the docker desktop and check for the container and run the container through port.
