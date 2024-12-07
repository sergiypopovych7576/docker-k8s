docker run --name mongodb -d -p 27017:27017 mongo:latest
docker run --name mongodb -d -v data:/data/db --network goals-net mongo:latest