A basic docker compose configuration. Includes the use of a YAML file.

Runs on port 80.


##Requires Docker


##Requires Docker Compose
sudo curl -L "https://github.com/docker/compose/releases/download/1.28.6/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version

##to run:
docker-compose up -d
navigate to localhost (or IPAddress:80)
Watch it work magic