sudo su
apt update && apt upgrade -y
apt install docker.io docker-compose
docker-compose -f win10.yml up