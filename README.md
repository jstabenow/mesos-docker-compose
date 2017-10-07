# Lightweight Mesos Toolbox for OSX

### Included:
* Mesos-Master
* Mesos-Agent
* Mesos-DNS
* Zookeeper

### Build for my Sys-ENV:
* OSX 10.12.6 (16G29)
* Docker 17.09.0-ce-mac35 (19611)

```sh
$ git clone https://github.com/jstabenow/mesos-toolbox
$ cd mesos-toolbox
$ docker-compose up
$ docker-compose down
```

## Available Endpoints:
* Mesos-Master: http://localhost:5050
* Mesos-Agent: http://localhost:5051
* Mesos-DNS: http://localhost:8123
* Zookeeper: zk://localhost:2181