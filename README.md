# Multi threading demo in Java

### Prerequisites
- JDK
- docker
- docker-compose

# Commands
- To run the app, under the app directory, run the command:
```
docker-compose up
```
To shutdown, under the app directory ,  run the command:
```
docker-compose down --rmi
```

- To get threadump for the app named DeadlockDemo, run:
```
jcmd $(pgrep -f DeadlockDemo) Thread.print
```

- To check docker cpu/memory usage, run:
```
docker stats
```