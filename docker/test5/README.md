# Commandes
## attention à bien vous situer dans le répertoire qui comprend Dockerfile et entrypoint.sh
```bash
docker build -t my-alpine-job .

```
## attention à bien avoir créé un chemin local
```bash
docker run -it -v /chemin/local:/data my-alpine-job

```