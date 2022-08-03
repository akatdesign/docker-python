## docker-python


**環境構築**
``` bash
$ cd docker-python/
$ docker compose up -d --build
$ docker compose exec python3 bash
``` 
**環境から抜ける**
```bash
$ exit
$ docker compose down
$ docker image rm imageid
```
**確認**
```bash
$ docker image ls
$ docker container ls
```
