
docker build -t node-websocket-push .

docker run -p 8080:8080 -d node-websocket-push:latest

go to: http://localhost:8080

