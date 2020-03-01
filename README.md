# ctfd-theme

## HELP


* executar ctfd
```bash
docker run -p 8000:8000 -it ctfd/ctfd
```
* pegando o ID do CONTAINER
```
$ docker ps
CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS              PORTS                    NAMES
fd9cd97481e5        ctfd/ctfd           "/opt/CTFd/docker-en…"   2 minutes ago       Up 2 minutes        0.0.0.0:8000->8000/tcp   magical_northcutt
```

* copiar arquivo do docker para o local
```bash
docker cp <CONTAINER ID>:/opt ./local/
```
* copiar arquivo do local para o docker
```bash
docker cp local/themes/ <CONTAINER ID>:/opt/CTFd/CTFd/
```
