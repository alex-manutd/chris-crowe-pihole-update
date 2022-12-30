# chris-crowe-pihole-update

cd ~/docker-pihole-unbound/one-container (OR WHEREVER docker-compose resides) |
docker compose pull #pulls the latest images |
docker compose up -d --no-deps --force-recreate #restarts containers with newer images |
docker system prune --all #deletes unused images |
#no need to stop or manually delete container
