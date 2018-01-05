# docker-kafka-stack
Docker kafka stack for Swarm

To deploy a kafka stack on Docker swarm, use these step:

```
docker network create --driver overlay kafka-net
docker stack deploy -c docker-compose.yml kafka
```
