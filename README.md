# Taiga-Docker
Taiga on Docker

to download this git :

git clone https://github.com/Aymeric29bzh/Taiga-Docker.git 

WARNING : 
TO CHANGE PORT GO INTO DOCKER-COMPOSE.YML and change...
If you want you can change Ports But if you change the port you have to add it to the IP address of the API 

First Step :
Go into taiga-conf -> conf.json
Change "api" with your IP.

SECOND Step :

Make docker-compose up

You should have an error at this step because the database wasn't initialize, to repair this restart the taiga
 Front :
 
 docker restart taiga-docker_taiga_1
 
 
