# docker cli commands
docker run  8080:8080 applayer/node-web-appode-web-app

# docker-compose commands
## start containers
docker-compose up       
## rebuild images and start containers
docker-compose up --build   
## start the commands in the background.
docker-compose up -d    
## stop all containers
docker-compose down     
## restart policies
"on", always, on-failure, unless-stopped