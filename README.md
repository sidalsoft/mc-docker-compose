# MC-docker-compose

### Runbook:

``````
docker compose down
sudo docker compose up -d mc1
sudo docker compose up -d mc3

// sleep 2s

sudo docker compose up -d mc2 
sudo docker logs -f mc1
``````