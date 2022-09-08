# MC-docker-compose

### Runbook:

``````
sudo docker compose up -d mc1
sudo docker compose up -d mc3

// sleep 5s

sudo docker compose up -d mc2 
sudo docker logs -f mc1
``````