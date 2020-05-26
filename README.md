# docker-3
THIS PROJECT IS ON JOOMLA AND MYSQL SERVER ON LINUX.
FOR THAT WE HAVE TO INSTALL JOOMLA. 

# Docker Compose
Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application's services. Then, with a single command, you create and start all the services from your configuration. ... Run docker-compose up and Compose starts and runs your entire app.

# prerequisites 
FIRST YOU SHOULD HAVE DOCKER AND DOCKER-COMPOSE IN YOUR SYSTEM .THEN YOU SHOULD INSTALL JOOMLA IMAGE AND MYSQL IMAGE IN LINUX TERMINAL. YOU SHOULD ALSO INSTALL MYSQL SERVER.FOR INSTALLING MYSQL YOU SHOULD USE YUM COMMAND.FIRST U HAVE TO CONFIGURE YUM THEN AFTER U CAN USE YUM COMMAND

docker pull joomla

docker pull mysql

yum install mysql

# code
mkdir myproject

vim docker-compose.yml

EXTENSION SHOULD YML ONLY WRITE THE CODE IN docker-compose.yml file

RUN YOUR CODE

THEN RUN YOUR CODE BY

docker-compose up

AND FOR STOPING IT USE COMMAND

docker-compose stop/down
