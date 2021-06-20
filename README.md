# Distributed_System-Second_Floor
This is a National Chengchi Univercity Distributed System Finals Demo.
The following steps is a tutorial of how to run the project.

##Requests.
    Flask==0.11.1 requests==2.18.4

##Step. 1.
Git clone the repo.

##Step. 2.
Start the Docker compose.
    docker-compose build --pull
    docker-compose up -d
Check the status of the containers.
    docker-compose ps

##Step. 3.
Run the server.
    python3 service.py
