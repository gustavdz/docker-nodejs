# docker-nodejs
 docker practice with node.js and GCP
 
# Docker commands
## Build the image for docker
 docker build -t docker-nodejs .
## List the images
 docker images
## Run the image docker-nodejs
 docker run -it -p 4000:3000 docker-nodejs
## Run the image docker-nodejs as a service
 docker run -d -p 4000:3000 docker-nodejs
## List all docker running processes
 docker ps
## Stop the running image by ID
 docker stop << id >>
