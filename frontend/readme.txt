docker run --name ui -d -p 3000:3000 ui
docker run --name ui -d --network goals-net -p 3000:3000 ui