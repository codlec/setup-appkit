# Codlec sveltekit setup

```}
# docker network create backend
# docker network connect backend postgres-db
# docker network connect backend appkit-codlec
# docker network connect backend seq-server
# docker network inspect backend

no usar
echo 'tuClaveSegura' | docker run --rm -i datalust/seq config hash

```

> docker login registry.codlec.com
> docker pull registry.codlec.com/appkit:latest

# setup-appkit

docker rm -f postgres-db
