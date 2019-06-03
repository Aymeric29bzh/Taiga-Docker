# Taiga-Docker
Taiga on Docker


First Step :

Go into docker-compose.yml 
Remplace with your IP into API_NAME.

If you want you can change Ports

Second Step :
Go into taiga-conf -> conf.json
Change "api" with your IP.

Third Step :

Make docker-compose up

You should have an error at this step because the database wasn't initialize, to repair this restart the taiga
 Front :
 
 docker restart taiga-docker_taiga_1
 
 
