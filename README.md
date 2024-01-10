# IBC Monitoring Starter Solution


# Commands to Install Software:
sudo apt-get update

# Install Docker
sudo apt-get install curl
curl -sSL https://get.docker.com | sh

# restart

sudo usermod -a -G docker $USER
sudo systemctl start docker
sudo systemctl enable docker
docker -v

sudo apt-get install docker-compose-plugin
docker compose version 

# download files

# navigate terminal to <solution files>/logging
./setup_logging.sh

docker compose build

# Starting the solution
./start.sh
or
Double click start.sh in the file explorer and select run in terminal

# Stopping the solution
./stop.sh
or
Double click stop.sh in the file explorer and select run in terminal

# Website links:
Dashboard -    http://localhost:3000/

# log files are found at:
/var/log/containers/



