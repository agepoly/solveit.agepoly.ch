# solveit.agepoly.ch

[solveit](http://solveit.agepoly.ch) website

## Launching on your machine

Have [docker](https://www.docker.com/) installed.

```
docker build -t solveit .
docker run --name solveitprocess -d -p 8080:80 solveit
```

And when you're done:

```
docker stop solveitprocess
docker rm solveitprocess
```
