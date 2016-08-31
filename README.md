# dockerdash

[![Build status](https://ci.appveyor.com/api/projects/status/q52dkb8di4578mh9?svg=true)](https://ci.appveyor.com/project/stefanprodan/dockerdash)


Docker dashboard built with ASP.NET Core, Docker.DotNet, SignalR and Vuejs.

Compatible with Docker v1.12, requires docker socket to be mounted as a volume.

### Run

```
docker run -d -p 5050:5050 -v /var/run/docker.sock:/var/run/docker.sock --name dockerdash stefanprodan/dockerdash
```

### Features

* Host information
* Containers real-time status via web sockets
* Container details, memory graph and logs
* Images information 

### Todo

* Swarm information
* Nodes status and details
* Services status and details