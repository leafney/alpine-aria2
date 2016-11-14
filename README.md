#### Docker + Alpine + Aria2

#### build

```
$ docker build -t="leafney/alpine-aria2" .
```

#### run aria2 docker

```
$ docker run --name aria2 -p 6800:6800 -d -v /boxvalume/aria2pan:/aria2down leafney/alpine-aria2
```
