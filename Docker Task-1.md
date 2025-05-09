Task Description:

Install docker on EC2 and explore the docker commands (docker images, containers, volumes, network)


Solution :

Exploring Docker commands:

1. docker --version
2. sudo docker images
3. sudo docker ps
4. sudo docker ps -a
5. sudo docker run -d -it --name web1 httpd:bookworm
6. sudo docker volume ls
7. sudo docker volume create volume1
8. sudo docker network ls
9. sudo docker run -d -it --name web2 -p:8081:80 --mount type=bind source=/home/ubuntu,target=/tmp httpd:bookworm


<img width="715" alt="image" src="https://github.com/user-attachments/assets/ead1b1d8-527b-40b0-a042-e980f105bedb" />

![image](https://github.com/user-attachments/assets/d55978f0-1f2b-4d58-b785-272e163aeddc)

![image](https://github.com/user-attachments/assets/58e3aa62-d7b5-4413-a0a9-942df9b38a81)


