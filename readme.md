## Installation (With docker)
Download docker-compose.yml .env from source

edit .env file RELAY_DOMAIN

Generate actor key:

openssl genrsa 2048 > actor.pem
docker-compose pull && docker-compose up -d
