docker-yify-pop
===============

Docker build file for yify-pop (Popcorn-time style app with Web UI for YIFY content). You need to have https://www.docker.com/ installed and running to make this useful

To Run
------

```
docker run -d --name yify-pop -p 4000:4000 -p 8889:8889 kim0/yify-pop
```

To build
--------

```
git clone https://github.com/kim0/docker-yify-pop.git
docker build -t yify-pop-custom docker-yify-pop
```
