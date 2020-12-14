# Simple docker example following udemy course

docker build example
```
$ docker build -t servers/simpleproject .
```

running with mapped port
```
$ docker run -p 8080:8080 servers/simpleproject
```