
### Structure
```
~/opt-kds-shipper/htdocs/Dockerfiles
├── README.md
├── redis
│   └── Dockerfile
├── filebeat
│   ├── Dockerfile
│   └── kds
│       └── filebeat.yml
├── log
│   └── 2015-02-23
├── docker-compose-yml

```         


### Installation docker
```
$ sudo apt-get update
$ sudo apt-get install docker-engine
$ sudo service docker start
```
### Installation docker compose
```
$ pip install docker-compose
$ curl -L https://github.com/docker/compose/releases/download/1.5.2/run.sh > /usr/local/bin/docker-compose
$ chmod +x /usr/local/bin/docker-compose
```
### runing
```
~/opt-kds-shipper/htdocs/Dockerfiles 目录下
docker-compose build & docker-compose up -d 
```
