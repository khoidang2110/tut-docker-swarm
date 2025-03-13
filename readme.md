các bước chạy test:

1. docker swarm init
2. docker build -t my-node-app:latest .
3. docker stack deploy -c docker-compose.yml my_app