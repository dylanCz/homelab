# Server

Some work needs done on the server that is running your homelab!

## Create your Doco-cd docker compose file

Take the docker-compose.yml file in this directory and place it on your server.

## Create your Doco-cd poll config file

Take the poll.yaml file in this directory and place it in the same folder as the docker-compose.yml file in the above step. Make sure to update it to point at your own github repository.

## Create your secrets.env file

Create a secrets.env file storing any secrets you need for your homelab. Notably you will need a GIT_ACCESS_TOKEN.

## Done!

At this point, run `docker compose up -d` and you should be good to go! Use `docker logs doco-cd` to check the logs of the Doco-cd container.
