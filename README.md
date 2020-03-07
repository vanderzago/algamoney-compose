# algamoney-compose

* Incluir no /etc/hosts da maquina host (local)
127.0.0.1 algamoney-db
127.0.0.1 algamoney-api

docker-compose up -d --build
docker-compose logs -f
docker-compose stop
docker-compose down
docker-compose down --volumes
docker-compose config (ver o q sera applicado)

docker stats (ver consumo de infra dos containeres)

